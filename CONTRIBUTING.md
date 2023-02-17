# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:omec-5g-smf_master_amd64.rock docker-daemon:omec-5g-smf:master
docker run omec-5g-smf:master
```
