# Adamnite-Testnet-Beta


### Kurulum / Instalation 
Repo private olduğu için access tokene ihtiyacımız var, bunun için;

Since the repo is private, we need access tokens, for this;

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
Move the private key that was generated to the keystore directory in the account1 folder.

Oluşturulan private keyi, account1 klasöründeki keystore dizinine taşıyın.
```
./nite --datadir account1 --port 30312 --nat extip:"your IPV4 address" --bootnodes 'gnite://c868aa9d1d79714d82b13baad504877ac7d0404999782f2b915b5588b9322de8ef137f2d225f34431985894f65ea5634332f178c32b51d23e09842e2d078bec9@38.17.51.24:0?discport=30301' --allow-insecure-unlock --unlock "your account's public address" --stake
```

### Sending Transactions
First, make sure you are in the nite-test directory. 

Öncelikle, nite-test dizininde olduğunuzdan emin olun.

Check your balance by running ``nite-test --balance "your public address"``

Bakiyenizi bu komutu çalıştırarak kontrol edin ``nite-test --balance "your public address"``

```
./nite-test --sendaddr "the address you want to send coins to" --recaddr "your public address" --amount "the amount you want to send" --keyfile "the directory where you saved your keyfile in the account creation step --password "your password from the previous step"
```

Run nite-test -h for help and additional commands.

Yardım ve ek komutlar için nite-test -h komutunu çalıştırın.
