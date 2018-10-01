# Equihash miner for NiceHash compiled with CPU_XENONCAT support.

Based on latest source as of image build time.

Source code and instructions: https://github.com/nicehash/nheqminer

## tl;dr

`git clone git@github.com:taskinen/nheqminer.git`

`cd nheqminer`

`docker build -t nheqminer .`

`docker run -d -ti nheqminer -u <YOUR_BITCOIN_ADDRESS>`

That will start the miner in background and pay the profits to your Bitcoin address.

You can monitor the progress from https://www.nicehash.com/?p=miners&addr=YOUR_BITCOIN_ADDRESS
