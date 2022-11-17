# Adamnite-Testnet-Beta


### Sistem Güncellemesi Yapalım
``
sudo apt update && sudo apt upgrade -y
``

### Kurulum
Repo private olduğu için access tokene ihtiyacamız var, bunun için;
settings -> developer settings -> personal access tokens -> tokens classic -> generate new token
``
git clone https://"access-token"@github.com/Adamnite/goAdamnite.git
``
``
 git clone https://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@github.com/Adamnite/goAdamnite.git
``
``
chmod u=rwx,g=r,o=r ./nite
``
``
./nite --datadir account1 init test.json
``
``
./nite account new
``
``
./nite --datadir account1 --port 30312 --nat extip:"your IPV4 address" --bootnodes 'gnite://c868aa9d1d79714d82b13baad504877ac7d0404999782f2b915b5588b9322de8ef137f2d225f34431985894f65ea5634332f178c32b51d23e09842e2d078bec9@38.17.51.24:0?discport=30301' --allow-insecure-unlock --unlock "your account's public address" --stake
``
