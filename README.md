# Chia Faucet
This code is used to run on chia.crypto-faucet.ml

![изображение](https://user-images.githubusercontent.com/82159969/172866208-6303fa02-aa40-4d61-b19c-9b0e5c56dacb.png)


In total, my faucet makes more than 800 000 transaction, little bit later i'll publish second part - payment gateway that makes payments from chia wallet to users.

To run this project you need:
- vps at least 1 cpu 1gb ram 10 gb hdd
- webserver - nginx
- database - postgresql
- queue - rabbitmq


To run you need to install a database, rabbitmq, create users set passwords, and then perform **uwsgi --ini xch-faucet.ini**





Click on star if you found it usable or interesting.

![изображение](https://user-images.githubusercontent.com/82159969/172861331-183bd154-804a-4213-9455-1569b43a4d05.png)


BTW:
This is my first flask project, so, don't be harsh.
I found that my project was archived by web.archive.org
https://web.archive.org/web/20220103060115/https://chia.crypto-faucet.ml/
