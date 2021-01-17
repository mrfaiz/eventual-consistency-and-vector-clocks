# Vector Clock and Eventual Consistency 

## Requirment
1. python3
2. mininet
3. root permission


## Start 8 servers without clustering 
```
$ sudo python3 start_topology.py
```


## Start 8 servers with clustering (divide into two clusters, 1-4 in one and 5-8 in other cluster)
```
$ sudo python3 two_cluster_topology.py
```

## stop servers
```
CTR + C
```

## Virtual server in mininet
10.1.0.1 to 10.1.0.8
