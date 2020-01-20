Check if a remote address and port is accessible from a local machine or while running on a platform such as Kubernetes / PCF


To run, please curl the following:

```
<url>/ping/<domain or ip>/port
```
For example:

```
http://localhost:8080/ping/google.com/443
```
Will return `Yay, I could connect!`

```
http://localhost:8080/ping/google.com/332
```

Will return `Bummer, I couldn't connect after 5 seconds.`
