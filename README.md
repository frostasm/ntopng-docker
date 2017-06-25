# ntopng-docker

Docker Compose is used to analyze traffic from a MikroTik router as described in the [article](http://www.ntop.org/ntopng/how-to-analyse-mikrotik-traffic-using-ntopng/)

## Deployment

### Ports
 - 3000/TCP - ntopng web interface
 - 2055/UDP - nprobe NetFlow/IPFIX/sFlow collector flows port

### Command Line
 ```
docker-compose up -d
 ```

 ### Web UI

 http://127.0.0.1:3000  
 username: admin  
 password: admin  

## Installed packages:
```
ntopng                     3.1.170625-3081
ntopng-data                3.1.170625
nprobe                     8.1.170625-5792
pfring                     6.7.0-1303
pfring-dkms                6.7.0
```