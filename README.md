# Adamnite-Testnet-Beta

Instalation 
```
sudo apt update && sudo apt upgrade -y
```

Since the repo is private, we need access tokens, for this;

settings -> developer settings -> personal access tokens -> tokens classic -> generate new token

```
git clone https://"access-token"@github.com/Adamnite/goAdamnite.git
```

```
chmod +x gnite
```

```
./gnite account new
```

### Sending Transactions

Check your balance by running ``gnite-test --balance "your public address"``

```
./gnite --sendaddr "the address you want to send coins to" --recaddr "your public address" --amount "the amount you want to send"
```

### Staking

```
./gnite --sendaddr "your address" --recaddr "the account you want to stake your coins to (can be one of the public accounts listed in the beta testing channel)" --amount "the amount you want to send" --txtype true
```

Run ``./gnite-test -h`` for help and additional commands.

