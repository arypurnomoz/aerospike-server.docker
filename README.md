## Usage:

```sh
docker run \
  -v /data:/opt/aerospike/data \
  -v /aerospike.conf:/etc/aerospike/aerospike.conf \
  arypurnomoz/aerospike-server 

# or with an url (https not supported)
docker run \
  -v /data:/opt/aerospike/data \
  -e CONFIG_URL=http://aerospike/conf \
  arypurnomoz/aerospike-server 
```

