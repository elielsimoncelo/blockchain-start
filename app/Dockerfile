FROM java:8

WORKDIR /app

COPY *.war .
COPY *.jar .

# EXPOSE 8080

CMD tail -f /dev/null

# ENTRYPOINT [ "while true; do sleep 1000; done" ]
# java -Dspring.datasource.username=root -Dspring.datasource.password=root  -jar /app/webapp-runner.jar --port 8080 --expand-war /app/eleicoesonline.war
# java -Dspring.datasource.username=root -Dspring.datasource.password= -jar ./app/webapp-runner.jar --port 8080 --expand-war ./app/eleicoesonline.war
# java -Dspring.datasource.username=root -Dspring.datasource.password= -Dspring.datasource.useSSL=false -Dspring.datasource.verifyServerCertificate=false -jar ./app/webapp-runner.jar --port 8080 --expand-war ./app/eleicoesonline.war