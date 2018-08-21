## dBank Paper Wallet

Credits: This is a complete re-design of @Xeroc's [Steem Paper Wallet](https://github.com/xeroc/steem-paperwallet).

![dBank Paper Wallet Screenshot 1](https://github.com/dBankCore/dbank-paperwallet/raw/master/screenshot-1.png)

![dBank Paper Wallet Screenshot 1](https://github.com/dBankCore/dbank-paperwallet/raw/master/screenshot-2.png)

### Building From Source
#### Ubuntu dependencies
```
sudo apt-get install libcairo2-dev libjpeg-dev libgif-dev
```

Once the dependencies are installed, do:

    npm install
    npm run browserify

### Usage

    open dist/index.html

### Requirements

* You need to provide the dBank account name
* Passwords must be at least 16 characters long
