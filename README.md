# Layer 2 Ethereum Aggregator & Launchpad

L2ETH is a simple tool which allows you to easily deploy and/or connect to:
  - SKALE and Matic sidechains
  - Raiden State Channels
  - ZKSync Rollups

## Requirments
    - Docker
    - That's it.

## Usage

Clone the repo, navigate to the cloned directory and run the instance with:

```bash
docker-compose pull
chain=<INSERT CHAIN NAME HERE> deployOrConnect=<DEPLOY OR CONNECT keywork goes here> connecturl=DEFAULT  docker-compose up
```

Your logs for your chain with port information will appear in the console

To stop the containers use:

```bash
docker-compose down
```

### Development

Want to contribute? Great! Please send any pull requests to the `develop` branch.


### Todos

 - Add more offchain solutions and options

License
----

MIT