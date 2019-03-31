# classicbitcoin
ClassicBitcoin Full-Node Desktop Wallet
Release for Windows, wallets, Mac and Linux desktop wallets will be available soon, you can also build from source.

Please note that these releases are alpha releases and should be treated as such. Always test with small amounts.

    Unzip all files to desired directory
    Run ClassicBitcoinDesktopWallet-1.1.2.jar
Windows remark: On first-run, an error is expected after downloading the keys. Close and run the wallet again; it should work.
Become a full node!

Open port 7123 on your internet router. This will allow you to become a full node and thus, support the ClassicBitcoin network.
ClassicBitcoin Full-Node Desktop GUI Wallet - v1.1.2

Windows, Mac, Linux

You will need the latest JDK installed.

Windows cbtcd.exe and cbtc-cli.exe are in "classicbitcoin-master.zip"
Mac cbtcd / cbtc-cli included in zip.
Linux follow the build instructions in README.md
Keep your private keys safe! Always back them up right away!

Your wallet file is at -

Windows - %APPDATA%\CBitcoin\wallet.dat
Mac - ~/Library/Application Support/CBitcoin/wallet.dat
Linux - ~/.cbitcoin/wallet.dat

If you make an encrypted wallet.dat, don't lose or share the password!

To run ClassicBitcoinDesktopWallet-1.1.2.jar, double-click it or java -jar ClassicBitcoinDesktopWallet-1.1.2.jar.
Troubleshooting

    My wallet used to run, but now I get an error when opening it. How do I fix this? Your blockchain became corrupted. Please delete these files in your AppData folder. In a future release, a clean.bat file will be included that can be used to clear out this folder for you automatically.

