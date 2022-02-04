## Download example

### On the server

```
nc -nlvp 4444 < Math2.tar.gz
```

### On the client

```
nc -nv <ip> 4444 > data2.in

```



## Upload example

### On the server

```
nc -nlvp 4444 > data2.in
```

### On the client

```
nc -nv <ip> 4444 < Math2.tar.gz

```

### capture pcap

```
sudo tcpdump -i <int> -w <filename>
```
