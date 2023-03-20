### SETUP LINUX/MAC

alias specmatic='java -jar /Users/douglasqueiroz/Dev/specmatic/specmatic.jar'

### GET API

curl https://my-json-server.typicode.com/znsio/specmatic-documentation/pets/1

### RUN PROVIDER SIDE

specmatic test service.yaml --testBaseURL=https://my-json-server.typicode.com/znsio/specmatic-documentation

### RUN CONSUMER SIDE

specmatic stub service.yaml

### JSON SPEC CONSUMER SIDE

service_data/scooby.json
