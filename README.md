# BlueWallet - A Bitcoin & Lightning Wallet

[![GitHub tag](https://img.shields.io/badge/dynamic/json.svg?url=https://raw.githubusercontent.com/BlueWallet/BlueWallet/master/package.json&query=$.version&label=Version)](https://github.com/BlueWallet/BlueWallet)
[![CircleCI](https://circleci.com/gh/BlueWallet/BlueWallet.svg?style=svg)](https://circleci.com/gh/BlueWallet/BlueWallet)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
![](https://img.shields.io/github/license/BlueWallet/BlueWallet.svg)

Thin Bitcoin Wallet.
Built with React Native and BlockCypher API.

[![Appstore](https://bluewallet.io/img/app-store-badge.svg)](https://itunes.apple.com/us/app/bluewallet-bitcoin-wallet/id1376878040?l=ru&ls=1&mt=8)
[![Playstore](https://bluewallet.io/img/play-store-badge.svg)](https://play.google.com/store/apps/details?id=io.bluewallet.bluewallet)

Website: [bluewallet.io](http://bluewallet.io)

Community: [telegram group](https://t.me/bluewallet)

* Private keys never leave your device
* Lightning Network supported
* SegWit-first. Replace-By-Fee support
* Encryption. Plausible deniability
* And many more [features...](https://bluewallet.io/features.html)

Beta version, do not use to store large amounts!


<img src="https://i.imgur.com/hHYJnMj.png" width="100%">





## BUILD & RUN IT

* In your console:

```
git clone https://github.com/BlueWallet/BlueWallet.git
cd BlueWallet
npm install
npm start android
``` 
## ********************************************************
##  completed Installation on Windows by Kcod ,   above one it is okay to install on MacOS
##  add 'sudo' all instructions if there are permission problems with MacOS

git clone https://github.com/BlueWallet/BlueWallet.git  <br />
cd BlueWallet. <br />
npm install --force   <br />
sudo chown -R youraccount folderName <br />
react-native link     <br />
"operating Android Studio and open an emulator"   // this mement doesn't have error when compilling android code <br />
npm start android                                 // this one for Daemon <br />
react-native run-android      
## ********************************************************


## TESTS

```bash
npm run test
```


## MOTIVATION TO BUILD IT

I was not satisfied with existing iOS Bitcoin apps, especially with BreadWallet (the one I mainly used) where development stalled and they could not even deliver such features as SegWit, RBF and custom fees (at the times where custom fees were especially needed).
So I knew I could create one to use myself and let others use it.
I had experience with awesome bitcoin-js lib (javascript), and since I dont own any Macs, don't plan to and not going to learn ObjC/Swift - ReactNative (where you also write in javascript) was an obvious choice.


## LICENSE

MIT

## WANT TO CONTRIBUTE?

Grab an issue from [the backlog](https://github.com/BlueWallet/BlueWallet/projects/1), try to start or submit a PR, any doubts we will try to guide you.

Join us at our [telegram group](https://t.me/bluewallet) where we hangout :+1:
