# Basic Networking example with quagga 
To create the topology run the following command

```
$ docker-compose up
```

Network topology will look like the following diagram:

```
    +---------------[r1]------------+
    | 172.16.10.2/24                | 172.16.20.2/24
    |                               |
    | 172.16.10.3/24                | 172.16.20.3/24
  [h1]                             [h2]
```
