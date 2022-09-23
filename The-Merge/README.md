# A PoS world

<br>


## proposer/builder separation (PBS)

<br>


### resources

<br>

* [State of research: increasing censorship resistance of transactions under proposer/builder separation (PBS), by Vitalik et al](https://notes.ethereum.org/@vbuterin/pbs_censorship_resistance)


<br>

---

## tools 

<br>


### validators

* [Beacon Chain Explorer](https://prater.beaconcha.in/)


<br>

---


### Definitions


* LMD-GHOST: latest message drive greediest heaviest observed subtree, the fork choice rule determining which block is viewed as the current chain head.

* Casper FFG: the finality gadget used in Ethereum PoS which moves blocks from the "proposed" to "justified" to "finalized" stage.

* Gasper: Ethereum’s PoS implementation, a combination of the LMD-GHOST fork choice rule, Casper FFG, and the specific reward/penalty scheme.

* RANDAO: random number generation scheme used to select block proposers, sort validators into committees, etc.

* BLS: cryptographic signature scheme used for validator attestations.

* inactivity leak: validators which don’t submit attestations are penalized if the chain stops finalizing.

* slashing: validators which maliciously propose or attest to multiple blocks at the same height have their stake reduced.

* proposer boost: a modification to LMD-GHOST giving additional weight to blocks proposed earlier in the slot to defend against avalanche attacks, see an explanation of a 7-block reorg in the beacon chain while this update was being rolled out.

