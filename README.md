# Adamnite-Testnet-Beta

### Güncelleme yapıyoruz: 
```
sudo apt update && sudo apt upgrade -y
```

### Aşağıdaki adımları yapın:

Kendi github profilinizden aşağıdaki adımları izleyin.
settings -> developer settings -> personal access tokens -> tokens classic -> generate new token
Bu adımlardan sonra açılan pencerede 
 * repo
 * write:packages
 * gist
 * notifications
 * write:discussion
kutucuklarını işaretleyin ve en altta Generate Token tuşuna basın.
#### Yukarıdaki adımlardan sonra
 * "access-token" yerine --> ghp_tkUD99pU....................... şeklinde bir kod oluşacak onu yazın
 
</br>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/560QzDh/a1.png" alt="a1" border="0"></a>
<a href="https://ibb.co/bRtPffZ"><img src="https://i.ibb.co/prqxmm8/a2.png" alt="a2" border="0"></a>
<a href="https://ibb.co/BzpGZ8Z"><img src="https://i.ibb.co/znMFRKR/a3.png" alt="a3" border="0"></a>
</br>


```
git clone https://"access-token"@github.com/Adamnite/goAdamnite.git
```
```
cd goAdamnite/Ubuntu
```

```
chmod +x goAdamnite/Ubuntu/gnite
```
* Aşağıdaki komutu girdikten sonra şifre oluşturmanızı isteyecek. Şifre girdikten sonra bir süre bekletecek. sonra size public key ve secret key verecek. Not edin kaybetmeyin!!!
```
./gnite account new
```

```
screen -S adamnite
```
```
./gnite
```


### Token Gönderme: 
* [Discord](https://discord.gg/adamnite-921093307533230111) kanalından test token isteyin. Şimdilik @toucan dan dm ile isteyin. Public keyinizi dm atın.
* goAdamnite/Ubuntu klasörünün içinde olduğunuzdan emin olun.
* Yukarıda almış olduğunuz public key aşağıdaki --> "your public address" ile değiştirin 

Bakiyenizi kontrol edin:  ``./gnite-test --balance "your public address"``
* "the address you want to send coins to" --> göndermek istediğiniz kişinin adresi
* "your public address" --> sizin adresiniz
* "the amount you want to send" --> miktar girin

```
./gnite-test --sendaddr "the address you want to send coins to" --recaddr "your public address" --amount "the amount you want to send"
```

### Stake
* 
```
./gnite-test --sendaddr "your address" --recaddr "the account you want to stake your coins to (can be one of the public accounts listed in the beta testing channel)" --amount "the amount you want to send" --txtype true
```

Run ``./gnite-test -h`` for help and additional commands.

