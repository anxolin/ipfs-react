# Decentralized app example
Just a test to deploy a decentralized SPA web using IPFS.

Run the IPFS node:
```bash
ipfs init
ipfs daemon
```

Add the files to IPFS:
```bash
ipfs add -r .
```

Get the hash of the root, and visit `http://localhost:8080/ipns/<app-dir-hash>`:
* [http://localhost:8080/ipns/QmXc7Q9jToiJ63orxV9sWVQLkweWBH6EPCDiuoHT2Nyb9f](http://localhost:8080/ipns/QmXc7Q9jToiJ63orxV9sWVQLkweWBH6EPCDiuoHT2Nyb9f)
