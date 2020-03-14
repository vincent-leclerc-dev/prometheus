# Installation
 
Edit config file /tmp/promeheus.yml 

Set target app  ex: - targets: ['192.168.64.3:31316']

# Run 

docker run \                                                                     
    -p 9090:9090 \
    -v $(pwd)/tmp/prometheus.yml:/etc/prometheus/prometheus.yml \
    prom/prometheus

# Prometheus dashboard url

http://localhost:9090/

