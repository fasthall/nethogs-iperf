# nethogs-iperf
Nethogs and iperf installed on Ubuntu Trusty.

##Usage

###Start iperf server
```
docker run -d -p 5001:5001 --name iperf fasthall/nethogs-iperf
```

###Start nethogs
```
docker exec -t iperf nethogs
```
