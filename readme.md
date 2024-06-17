# 
helm charts 저장소입니다.

### Heapdump Test
```
# run
helm upgrade --install hd-test ./hd-test


# change label
kubectl label pod hd-test-6bbf8b7f9b-smwgj app.kubernetes.io/name=hd-test123 --overwrite
```
