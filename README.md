# classicbitcoin
ClassicBitcoin Full-Node Desktop Wallet
Release for Windows, wallets, Mac and Linux desktop wallets will be available soon, you can also build from source.

Please note that these releases are alpha releases and should be treated as such. Always test with small amounts.

[CBTC daemon and command-line app](https://github.com/ClassicBitcoins/cbitcoin/releases)

[Guide to setup CBTCWallet.jar can be found here!](https://github.com/ClassicBitcoins/cbtc-wallet)

    *Windows remark: On first-run, an error is expected. after downloading the cryptographic keys, close and run the wallet again; it should work. Join CBTC and Become a full node!)*

Open port 2050 on your internet router. This will allow you to become a full node and thus, support the ClassicBitcoin network.
CBTC Wallet - v1.0.9.50

Windows, Mac, Linux

You will need the latest JDK installed.

Linux follow the build instructions in README.md
Keep your private keys safe! Always back them up right away!

Your wallet file is at -

1. Windows - %APPDATA%\CBTC\wallet.dat
1. Mac - ~/Library/Application Support/CBTC/wallet.dat
1. Linux - ~/.cbtc/wallet.dat

If you make an encrypted wallet.dat, don't lose or share the password!


    My wallet used to run, but now I get an error when opening it. How do I fix this? Your blockchain became corrupted. Please delete these files in your AppData folder. In a future release, a clean.bat file will be included that can be used to clear out this folder for you automatically.

