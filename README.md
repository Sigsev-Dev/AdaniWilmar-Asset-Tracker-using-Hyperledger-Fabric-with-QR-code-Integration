## Hyperledger Fabric - Logistics

Adani-Wilmar is a multi-million dollar conglomerate which offers most of the essential kitchen commodities for Indian consumers, including edible oil, wheat flour, rice, pulses and sugar.

It also offers a range of staples such as wheat flour, rice, pulses and sugar and these products are offered under a diverse range of brands across a broad price spectrum and cater to different customer groups.

The vast array of commodities and the products in circulation make it essential for a traceability option to be integrated with every stages of a product in the supply chain, ranging through manufacture to retail.


Here assumption is that you have installed all [prerequisites](https://hyperledger-fabric.readthedocs.io/en/release-1.3/prereqs.html) that a standard Hyperledger Fabric requires.

Get solution
```
git clone https://github.com/dcentrum/Project-HLF-Logistics.git
cd code
```

You might need to use a certain version of nvm that needs to be installed separately
```
nvm installv11.9.0
```
### BlockServer
this is web server based on nodejs and expressjs. facilitates following things.
* Acts as client for Fabric network by using **Fabric-Client** sdk
* Acts like a web server that wraps all the fabric interaction logic as REST API (GET, POST endpoints).
* Bridge between a user interface layer and fabric network layer.


## Start Fabric
Run following commands in **BlockServer** folder to start network, install dependencies, enroll Admin and register user.

```

cd BlockServer

npm install

cd BlockFabric

sudo bash startFabric.sh

```

<!-- ## Start Web server
Run following commands in **BlockServer** folder to start the web server

```
node app.js
```

## Stop the network
To stop network after testing, run the given commands in **BlockFabric** folder
```
cd BlockFabric

./stop.sh
OR
ctrl+C (incase docker-compose up is used)
```

## Kill the network
To kill the complete network, use the **./teardown.sh** in **BlockFabric** folder

```
cd BlockFabric

./teardown.sh
``` -->


Thank you.
# Asset-Tracker-using-Hyperledger-Fabric-with-QR-code-Integration
# Kashyapdevesh-Asset-Tracker-using-Hyperledger-Fabric-with-QR-code-Integration
