## noble-device forked to use @abandonware/noble

Fork of [noble/noble-device](https://github.com/noble/noble-device) that uses [@abandonware/noble](https://github.com/abandonware/noble) under the hood for BLE and therefore works on Mac OS X Catalina.

Meant to be used with [my forked version of MetaWear SDK for Javascript](https://github.com/alexdpoon/MetaWear-SDK-JavaScript) that also uses [@abandonware/noble](https://github.com/abandonware/noble) 

### Installation

Don't install noble. If you already have it installed, do 

```
npm uninstall --save noble.
```

Then just do 

```
npm install --save "https://github.com/alexdpoon/MetaWear-SDK-JavaScript"
```

