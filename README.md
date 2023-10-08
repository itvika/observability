# observability

Go to the folder observability
## Grafana
    cd grafana

#### Build Image of grafana
    docker image build -t <image name>:<tag> .  
####    
    docker image build -t grafana:v0 .

#### Run Container of grafana
    docker run -d --rm --name grafana -p 3000:3000 -d grafana:v0
