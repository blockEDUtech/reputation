# reputation
Prototyping the blockEDU distributed reputation system based on UniTEC

Considering using devp2p kad with a DSHT overlay. This is similar to the Swarm bzz method where we will communicate with ethereum nodes until we find a node that speak `rec`. This peer will send a list of other nodes in it's lookup table that will bootstrap the connecting node into the reputation protocol.

First implementation: go-ethereum
