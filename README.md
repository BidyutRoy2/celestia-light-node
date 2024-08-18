# Run Celestia Light Node with One-command Script

<img src="https://i.ytimg.com/vi/9uL3jZe4mTY/maxresdefault.jpg" width="700"/>

## About Celestia
Celestia is a modular data availability network that securely scales with the number of users, making it easy for anyone to launch their own blockchain.
* [Twitter](https://x.com/CelestiaOrg)
* [Website](https://celestia.org/)
* [Discord](https://discord.com/invite/YsnTPcSfWQ)
* [Docs](https://docs.celestia.org/)
* [Github](https://github.com/celestiaorg)

#### This script allows you to set up and run a `Celestia Light Node` with a single command. Script automatically does the necessary setup, setup the Light node and runs it inside the screen.

## System Requirements

- Memory: 500 MB RAM (minimum)
- CPU: Single Core
- Disk: 100 GB SSD Storage
- Bandwidth: 56 Kbps for Download/56 Kbps for Upload

Note: The script only works on Ubuntu (20.04/22.04). 

## About Light Node
Light nodes allow anyone to directly verify data availability and interact with Celestia without centralized gateways or RPC providers. They perform [data availability sampling (DAS)](https://celestia.org/glossary/data-availability-sampling/) on the received headers, ensuring data availability. This is the most common way to interact with Celestia networks and enables Celestia to securely increase throughput for rollups as new light nodes join the network over time.

<div style="text-align: center;">
    <img src="https://docs.celestia.org/img/nodes/LightNodes.png" width="700"/>
</div>

## How to Use?

To use this script, run the following command in your terminal:
```bash
wget -q -O light.sh https://raw.githubusercontent.com/BidyutRoy2/celestia-light-node/main/light.sh && sudo chmod +x light.sh && ./light.sh
```

## Copy and Save Your Celestia Wallet Mnemonics Seed Phrase in NotePad
## To view the logs, use:
```
screen -r celestia-node
```
Restart Node
```
celestia light init --p2p.network celestia
```

Note: You can exit the screen with `CTRL A + D`. When you exit in this way, your node will continue to work on the screen. 


# ▄︻デ𝙂𝙚𝙩 𝙇𝙖𝙩𝙚𝙨𝙩 𝘼𝙞𝙧𝙙𝙧𝙤𝙥𝙨 & 𝙐𝙥𝙙𝙖𝙩𝙚𝙨═━一

### ▄︻デ𝙅𝙤𝙞𝙣 𝙏𝙚𝙡𝙚𝙜𝙧𝙖𝙢═━一 [🎀  𝐻𝒾𝒹𝒹𝑒𝓃 𝒢𝑒𝓂  🎀](https://t.me/hiddengemnews) 

