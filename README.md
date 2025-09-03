Docker assignment 
Architecture Block Diagram
    App / Log File --> Promtail --> Loki --> Grafana Dashboard
                              (Docker network)
File structure : : :
devops-assignment/
├─ docker-compose.yml
├─ promtail-config.yml
├─ loki-config.yml
├─ grafana/
│  ├─ provisioning/
│  │  ├─ datasources/datasource.yml
│  │  └─ dashboards/
│  │     ├─ dashboards.yml
│  │     └─ robot-logs-dashboard.json
├─ logs/
│  └─ sample.log        # put the given sample logs here
└─ .github/workflows/deploy.yml   # simple CI/CD

