# Blockchain-Tang-FishCoin

## Setup

1. Import dependencies via pip3
    1. `flask==1.1`
    1. `requests==2.2`

## Run

1. Run blockchain (Port 8000):
    1. `set FLASK_APP=blockchain.py`
    1. `flask run --port 8000`
    1. Open http://127.0.0.1:8000
    1. Whenever a block is mined, a dump of the chain is saved to `chain.json`
        1. When the server is restarted, this file is read to save the current chain state
1. Run frontend client (Port 5002):
    1. `python server.py`
    1. Open http://127.0.0.1:5002

### Demo

1. Add a fish metadata
1. Mint coin
1. Visit http://127.0.0.1:8000/chain to see fish
