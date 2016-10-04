# sample-keys

To check ssh rsa fingerprint:
```
$ ssh-keygen -lf .ssh/id_rsa.pub
```

2048 26:79:bb:d2:4e:9a:6a:a5:e3:4f:bc:67:65:05:2c:84  vcap@1940be76-9d47-491b-a9c5-9c3d4ceb0e48

- The first part (2048) is the key length in bits
- Second part is the fingerprint of the public key
- Third part is location of the public key file itself
