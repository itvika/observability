# Observability

Go to the folder observability
## Grafana
    cd grafana

#### Build Image of grafana
    docker image build -t <image name>:<tag> .  
####    
    docker image build -t grafana:v0 .

#### Run Container of grafana
    docker run -d --rm --name grafana -p 3000:3000 -d grafana:v0


## Prommetheus
    cd prommetheus

#### Build Image of prommetheus
    docker image build -t <image name>:<tag> .  
####    
    docker image build -t prommetheus:v0 .

#### Run Container of prommetheus
    docker run -d --rm --name prommetheus -p 9090:9090 -d prommetheus:v0
