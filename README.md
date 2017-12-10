# Do not use this

NiceHash was hacked on 6th of December 2017 so you probably don't want to use this now.

## Equihash miner for NiceHash compiled with CPU_XENONCAT support.

Based on latest source as of this image's push time. Compiled in Ubuntu 16.04.

Source code and instructions: https://github.com/nicehash/nheqminer

### tl;dr

`docker run -d -ti taskinen/nheqminer -u <YOUR_BITCOIN_ADDRESS>`

That will start the miner in background and pay the profits to your Bitcoin address.

You can monitor the progress from https://www.nicehash.com/?p=miners&addr=YOUR_BITCOIN_ADDRESS
