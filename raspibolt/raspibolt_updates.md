[ [Intro](README.md) ] -- [ [Preparations](raspibolt_10_preparations.md) ] -- [ [Raspberry Pi](raspibolt_20_pi.md) ] -- [ [Bitcoin](raspibolt_30_bitcoin.md) ] -- [ [Lightning](raspibolt_40_lnd.md) ] -- [ [Mainnet](raspibolt_50_mainnet.md) ] -- [ [FAQ](raspibolt_faq.md) ] -- [ **Updates** ]

------

### Beginner’s Guide to ️⚡Lightning️⚡ on a Raspberry Pi

------

# Updates

I try to keep track of my changes to the guide here, so you can see what parts I updated later on.

### 2018-03-23
* **Bitcoin**: added PDF version of "Mastering Bitcoin"
* **Bitcoin**: adjusted systemd unit files `bitcoind.service` , `getpublicip.service` and `lnd.service` to account for a problem with binding of bitcoind to port 18333 (see [discussion](https://bitcointalk.org/index.php?topic=3179045.msg32917243#msg32917243) on bitcointalk.org). Thanks, **@whywefightnet**! 

### 2018-03-22

* **Mainnet**: more stable switch to mainnet, more conservative wallet creation
* **Mainnet**: useful examples for `lncli`. Thanks **@raindogdance**!
* **Mainnet**: copy updated `bitcoin.conf` to user "admin" for credentials

### 2018-03-20

* **Lighting**: Add reference to LND issue 890 when macaroons are not created. 
* **Bitcoin** and **Lightning**: Copy credentials for `bitcoind` and `lnd` to user "admin" home directory. As this is a superuser anyway there's no sense in always switching to the user "bitcoin" session.


