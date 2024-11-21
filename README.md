This deploys a web service at <https://cert-example.chrisproject.org/>.

After deploying this repository and waiting about 5 minutes:

```
$ kubectl get certificate
NAME           READY   SECRET             AGE
cert-example   True    cert-example-tls   14m
```
