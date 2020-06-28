## noble-device forked to use @abandonware/noble

Fork of [noble/noble-device](https://github.com/noble/noble-device) that uses [@abandonware/noble](https://github.com/abandonware/noble) under the hood for BLE and therefore works on Mac OS X Catalina.

Meant to be used with [my forked version of MetaWear SDK for Javascript](https://github.com/alexdpoon/MetaWear-SDK-JavaScript) that also uses [@abandonware/noble](https://github.com/abandonware/noble) 

### Installation

Like the original MetaWear SDK for Javascript, this fork still requires Node 8 and XCode. If you already have Node 10+, you can downgrade to Node 8, or use nvm to allow your machine to run multiple version of Node in parallel (which is what I did).

Don't install noble. If you already have it installed, do 

```
npm uninstall --save noble.
```

Then just do 

```
npm install --save "https://github.com/alexdpoon/MetaWear-SDK-JavaScript"
```

