## grin-miner-ethos
grin-miner ethOS Mining OS integration (ethosdistro.com)

Works with ethos 1.3.3 (latest), other versions are not tested.

grin-miner version: 1.0.2-cuda-ocl-ethos

### Installation
```
# From rig:
git clone https://github.com/amnesium/grin-miner-ethos.git
cd grin-miner-ethos
./install
sudo reboot
```

### Ethos configuration
```
miner [worker] grin-miner
grin-miner=proxywallet farm@test.com
grin-miner=proxypool1 us-east.stratum.grinmint.com:4416
grin-miner=poolpass1 farmpw
grin-miner=flags ssl=on # or ssl=off
```

