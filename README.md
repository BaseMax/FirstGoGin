# First Go Gin

Building web service (API) using Gin in Go programming language and test its benchmark and performance. 

## Using

```
git clone https://github.com/BaseMax/FirstGoGin
or
go get https://github.com/BaseMax/FirstGoGin
go build
./main
```

### My Performance Benchmark

### Hardware

**CPU:** Intel Core i5-9400F @ 6x 4.1GHz [57.0°C]


```
wrk -c 400 -d 60s -t 8 http://127.0.0.1:8080 --latency
```

Result:

```
Running 1m test @ http://127.0.0.1:8080
  8 threads and 400 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency     9.40ms   27.87ms 594.20ms   98.86%
    Req/Sec    10.71k     1.33k   18.57k    75.86%
  Latency Distribution
     50%    3.72ms
     75%   12.08ms
     90%   21.94ms
     99%   38.84ms
  5088636 requests in 1.00m, 635.73MB read
Requests/sec:  84691.09
Transfer/sec:     10.58MB
```

© Copyright Max Base, 2021
