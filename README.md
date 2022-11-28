# Adamnite-Testnet-Beta

System Requirements - 5 core CPU | 8GB of RAM | 10GB of free HDD or SSD Space

### Instalation 
```
sudo apt update && sudo apt upgrade -y
```
```
sudo apt install make clang pkg-config libssl-dev libclang-dev build-essential git curl ntp jq llvm tmux htop screen unzip cmake -y
```

Since the repo is private, we need access tokens, for this;

settings -> developer settings -> personal access tokens -> tokens classic -> generate new token

```
git clone https://"access-token"@github.com/Adamnite/goAdamnite.git
```
```
cd goAdamnite/Ubuntu
```

```
chmod +x gnite
```
```
chmod +x gnite-test
```
```
./gnite account new
```
```
screen -S adamnite
```
```
./gnite
```


### Sending Transactions

Make sure your are in goAdamnite/Ubuntu directory and have test NITE.

Check your balance by running ``./gnite-test --balance "your public address"``

```
./gnite-test --sendaddr "your address" --recaddr "the address you want to send coins to" --amount "the amount you want to send --password "your password"
```

### Staking

```
./gnite-test --sendaddr "your address" --recaddr "the account you want to stake your coins to (can be one of the public accounts listed in the beta testing channel)" --amount "the amount you want to send" --txtype true --password "your password"
```

Run ``./gnite-test -h`` for help and additional commands.

