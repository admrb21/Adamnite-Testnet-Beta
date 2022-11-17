# Adamnite-Testnet-Beta


### Sistem Güncellemesi Yapalım
```
sudo apt update && sudo apt upgrade -y
```

### Kurulum
Repo private olduğu için access tokene ihtiyacamız var, bunun için;

settings -> developer settings -> personal access tokens -> tokens classic -> generate new token

```
git clone https://"access-token"@github.com/Adamnite/goAdamnite.git
```


```
chmod u=rwx,g=r,o=r ./nite
```

```
./nite --datadir account1 init test.json
```

```
./nite account new
```

```
./nite --datadir account1 --port 30312 --nat extip:"your IPV4 address" --bootnodes 'gnite://c868aa9d1d79714d82b13baad504877ac7d0404999782f2b915b5588b9322de8ef137f2d225f34431985894f65ea5634332f178c32b51d23e09842e2d078bec9@38.17.51.24:0?discport=30301' --allow-insecure-unlock --unlock "your account's public address" --stake
```

### Sending Transactions

```
.\nite-test.exe (.\nite.test if you are on Linux) --sendaddr "the address you want to send coins to" --recaddr "your public address" --amount "the amount you want to send" --keyfile "the directory where you saved your keyfile in the account creation step --password "your password from the previous step"
```
