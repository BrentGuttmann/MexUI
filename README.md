# BitMex-UI

A graphical UI for BitMex

# Install

(tested on Ubuntu 18LTS fresh install)

sudo apt-get update

sudo apt-get upgrade

sudo apt-get install -y gcc g++ make libncurses5-dev libreadline6-dev libssl-dev libgdbm-dev libc6-dev libsqlite3-dev libbz2-dev xz-utils patch wget tar curl bzip2 zlib1g-dev python-bsddb3

sudo apt-get install -y libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev python-dev python-pip python-dev build-essential python-wxtools

sudo pip install Pyro4==4.60 bitmex-ws future jsonref jsonrpclib-pelix websocket

sudo pip install -U requests

# Run the script

git clone cd into MexUI directory and start:

python MexBot API_KEY=<YOUR_API_KEY> API_SECRET=<YOUR_API_KEY_SECRET> LiveNET=True AccName=<NAME_OF_ACCOUNT> TAG=<TRADETERM_TAG>

API_KEY= Use your API key. No space, no quotes

API_SECRET= Use your API secret. No space, no quotes

LiveNET= Optional: Leave this out and script will start on testnet , use True for realnet ( after experimenting a little on Testnet )

AccName= Optional: Leave this out and it will default to "PublicAcc" else use whatever name you want to give to this account

TAG= Optional: The tag to listen to for the trading terminal

# Run the trade terminal

Open a new terminal and run from the same folder:

python Terminal.py

N-joy :)