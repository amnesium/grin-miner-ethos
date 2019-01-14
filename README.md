### grin-miner-ethos
grin-miner ethOS Mining OS integration (ethosdistro.com)

Works with ethos 1.3.3 (latest), other versions are not tested.

grin-miner version: 0.5.2-cuda-ocl-ethos

SSL enabled in grin-miner.stub.conf, comment the line "stratum_server_tls_enabled = true" to disable SSL.

```
miner [worker] grin-miner
grin-miner=proxywallet farm@test.com
grin-miner=proxypool1 us-east.stratum.grinmint.com:4416
grin-miner=poolpass1 farmpw
```

