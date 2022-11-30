此為配合Mac M1系列調整的SonarQube Docker Server建立

建立的方式參考自 https://github.com/sonar-scala/docker-sonarqube

1. 執行`docker-compose -f docker-compose.yaml up -d --build`啟動Server
2. http://localhost:59000 (預設 admin/admin)