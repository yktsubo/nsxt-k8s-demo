# Tips

```
kubectl create secret generic nsx-ca --from-file=./nsx-ca.crt
kubectl create secret tls nsx-system --cert=./ncp-client.crt --key=./ncp-client.key
kubectl create secret tls lb-secret --cert=lb.crt --key=./lb.key
```
