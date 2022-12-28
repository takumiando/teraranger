# teraranger

A simple tool for TERABEE TeraRanger Evo Mini in POSIX.

## 1PX, long range(default)
```
$ ./teraranger
206
204
206
204
206
203
206
207
...
```

## 2PX, long range
```
$ ./teraranger -p 2 -r long
122,155
119,156
121,157
118,154
121,152
119,155
124,156
121,156
...
```

## 4PX, short range
```
$./teraranger -p 4 -r short
23,153,143,156
119,153,142,153
121,150,142,154
125,151,143,154
123,150,140,153
123,149,142,158
122,148,145,156
124,148,142,158
...
```
