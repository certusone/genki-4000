# genki-4001

Interim community testnet before GoS resumes on Jan 3rd/4th. On Dec 28th, we are attempting a hard fork from block 50,000 of `genki-4000` as was passed in a governance proposal.

If this fails to produce a correct state, the plan is to iterate till we get it right.  

The network will do a quick start, and everyone can join in later by creating a validator on the running the chain. There is NO disadvantage if you join later - after all, testnet tokens are worthless.

- Please register only if you intend to be present at genesis.

- It would be fantastic if we could get this testnet running alongside GoS.
  If you can, run this in addition to your GoS nodes.

- This testnet is coordinated in the #cosmos-validators:matrix.org channel.

## Getting started

### Upgrading from genki-4000

We are attempting a hard fork from `genki-4000` on December 28th.

if you were validating on `genki-4000`,

1. Halt your node.
2. Consider backing up `$HOME/.gaiad/data`. This will make it possible to restart `genki-4000` if the hard fork state is invalid.
3. Download the new genesis file from `https://raw.githubusercontent.com/certusone/genki-4000/master/genesis-final.json`
4. `gaiad unsafe-reset-all`
5. `gaiad start`



### Genesis collection

DONE

~Submit your gentx at https://genesis.certus.one~

### Launch (once genesis collection is done)

Download the final genesis file from `https://raw.githubusercontent.com/certusone/genki-4000/master/genesis-final.json` and store it as `~/.gaiad/config/genesis.json`.

Add the following seed nodes:

    ed6b6d5019563b40e81ae29c80c712fce7ae68f0@seed01.genki.certus.one:26656
    db02715d74e68c48884aad9e9c7dac6bc7f3c7cd@35.224.105.191:26656


Persistent peers :
74745f645a7102f519b0a3169d56eb0767f1bfb6@45.77.53.208:26656
