# walrus_monitor
Self-hosted, read-only BatteryEVO Walrus G4 monitor with Docker deployment, local telemetry, solar production, battery status, house/grid power, historical charts, day drill-down, solar savings estimates, CSV/JSON exports, and a local API.

unzip walrus-monitor-v0.6.0.zip
cd walrus-monitor

cp .env.example .env
nano .env

docker compose config
docker compose up -d --build
docker compose ps
