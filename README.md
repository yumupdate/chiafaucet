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


BTW:
This is my first flask project, so, don't be harsh.
