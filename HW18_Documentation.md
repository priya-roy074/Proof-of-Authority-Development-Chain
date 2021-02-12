## Blockchain HW Assigment Markdown

### Documentation:

* Download files in this repository and and then initialize Node A using the following code in git bash:


* ./geth init kikinet.json --datadir nodeA 

* then do the same for Node B

* $ ./geth init kikinet.json --datadir nodeB

### Then begin mining next!


* Now type the following code:

* ./geth --datadir nodeA --unlock 0x9a7bd539E344c68bA4bf10fC3bC706236f6D2fCA --mine --rpc --allow-insecure-unlock

* Then type the password: pup123

* Then copy paste the enode address: self=enode://2a7a4b84f2ccf87c2800440f5213ebab41a03414184363ae350e0f8acbaa04d2780ae3c8993b70985208cb5a0c00a1087705e4c75b2ccf527dd74db6dc9ec182@127.0.0.1:30303

* Next open a new gitbash window and type the following code:

* geth --datadir nodeB --unlock 0x710b5eE08cbe63Bdb55bc9acAaB947cCc27bc34c --mine --port 30304 --bootnode "enode://2a7a4b84f2ccf87c2800440f5213ebab41a03414184363ae350e0f8acbaa04d2780ae3c8993b70985208cb5a0c00a1087705e4c75b2ccf527dd74db6dc9ec182@127.0.0.1:30303" --ipcdisable  --allow-insecure-unlock

* type the passwork: pup123

### Send Transaction - Dowloand and open my crypto


*Set up a custom node: 
![custom-node](Images/setting_up_custom_net.png)

* Then click on "view and sent" and upload your keystore file in the NodeA folder and type the password "pup123" 

* Paste in the public address of Node B and send transaction