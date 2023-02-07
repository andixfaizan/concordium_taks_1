# Concordium_Taks_1
## MY SUBMISSION for taks 1

- My Mainnet Concordium wallet : 3UaBdbhafZTsmk52wBq4e3RoDT4EyFxMBrVh6aYBXWsWrsQGeA

## First
## Install Rust

### install Rust [Rustup](https://rustup.rs/) using 

````
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
````
Select 1 to default install and Enter
After Installing Finish Configuration Path
````
source "$HOME/.cargo/env"
````
## Next Install he Wasm using this command 
````
wget https://distribution.concordium.software/tools/linux/cargo-concordium_2.7.0
````
Rename the file make it executable and move it to system path
````
mv cargo-concordium_2.7.0 cargo-concordium
chmod +x cargo-concordium
sudo mv cargo-concordium /usr/local/bin
cargo-concordium --version
````
## Install Concordium Client
````
wget https://distribution.concordium.software/tools/linux/concordium-client_5.0.2-0
````
Rename the file make it executable and move it to system path
````
mv concordium-client_5.0.2-0 concordium-client
chmod +x concordium-client
sudo mv concordium-client /usr/local/bin
````
## Install Web Wallet

install [chrome extension](https://chrome.google.com/webstore/detail/concordium-wallet/mnnkpffndmickbiakofclnpoiajlegmg?hl=en-US)

## Creating Testnet Account

- creating ID using Concordium testnet IP don't forget to save 24 pharse words

- create an account

- and request the testnet token in wallet tesnet

Backup private key using file then move it to your directory

Then run to verify your concordium client

```
concordium-client config account import <YOUR PUBLIC ADDRESS.export> --name <Your-Wallet-Name> 
````
Output 
<img width="1059" alt="Screenshot 2023-02-07 at 16 19 30" src="https://user-images.githubusercontent.com/55140596/217210062-ca87318d-85ba-456f-93c4-6b9e786dafb8.png">























