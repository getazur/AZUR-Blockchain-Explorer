# AZUR-Blockchain-Explorer
Block explorer for AZUR CryptoNote v7 based cryptocurrency.

#### Installation

1) It takes data from daemon karbowanecd. It should be accessible from the Internet. Run karbowanecd with open port as follows:
```bash
./azurd --enable-blockexplorer --rpc-bind-ip 0.0.0.0 --enable-cors=*
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
