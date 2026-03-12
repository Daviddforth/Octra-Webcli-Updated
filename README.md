# Octra WebCLI v0.04.07 Full Setup & Settings Guide

This guide walks through:

- Installing the Octra WebCLI from scratch
- Launching the local wallet interface
- Importing wallets
- Updating the RPC and Explorer settings

It’s recommended to install everything again from the beginning to avoid issues with older versions

## 1. Download the WebCLI

Go to the repository:


https://github.com/octra-labs/webcli

Clone the repo:

```bash
git clone https://github.com/octra-labs/webcli.git
cd webcli
```
## 2. Git pull 
```
git pull
```
This will download the latest updates from the repository.

## 3. Run the Setup Script
Linux / macOS
```
./setup.sh
```
If permission is denied:
```
chmod +x setup.sh
./setup.sh
```

Windows
```
setup.bat
```

## 4. start the wallet:
```
./octra_wallet
```


## Then open your browser and go to:
```
http://127.0.0.1:8420/
```

This opens the local WebCLI interface

The wallet runs locally, meaning your keys remain on your device

## 5. Update WebCLI Network Settings
After installing and launching the wallet, you must update the network settings
Open settings 

Then update the following fields
RPC URL
```
http://46.101.86.250:8080/rpc
```

Explorer URL
```
http://octrascan.io
```

Make sure you save the changes.

These settings allow your WebCLI wallet to:

connect to the correct Octra testnet RPC

link transactions to the Octra explorer

## 6. Restart (Recommended)

After changing settings:

Logout from the wallet

Restart the WebCLI

Open the interface again
