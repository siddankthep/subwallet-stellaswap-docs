# Create a wallet with SubWallet

SubWallet is the comprehensive non-custodial wallet solution for Polkadot, Substrate & Ethereum ecosystems. Built on top of Polkadot {.js}, SubWallet focuses on improving UX & UI. We envision a crypto wallet as a Web3 multiverse dApp through which users can enjoy multi-chain services with utmost ease and absolute security. 
This guide will show you how to manage your accounts, connect to and interact with StellaSwap using SubWallet!

## Step 1: Install SubWallet

SubWallet is available on a range of platforms for you to choose from:

1. A **browser extension** which is available on [Google Chrome](https://chromewebstore.google.com/detail/subwallet-polkadot-wallet/onhogfjeacnfoofkfgppdlbmlmnplgbn), [Brave](https://chromewebstore.google.com/detail/subwallet-polkadot-wallet/onhogfjeacnfoofkfgppdlbmlmnplgbn), [MS Edge](https://chromewebstore.google.com/detail/subwallet-polkadot-wallet/onhogfjeacnfoofkfgppdlbmlmnplgbn) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/subwallet/).

2. A **mobile app** which is available on the [App Store](https://apps.apple.com/us/app/subwallet-polkadot-wallet/id1633050285) and [Google Play Store](https://play.google.com/store/apps/details?id=app.subwallet.mobile).

3. A web dashboard that does not require any downloading and can be accessed through https://web.subwallet.app

For this tutorial, we will walk you through the process of creating a wallet using the browser extension.

## Step 2: Setup an account

Once you have installed the extension, you'll have the option to **create, import** or **attach a watch-only account**.

![Browser extension create screen](/subwallet-imgs/subwallet-1.png)

### Create a new account

To create a new account, click on **Create a new account**.

![Create new account](/subwallet-imgs/subwallet-2.png)

You will then need to create your master password which keeps all of your accounts secure. Once you have entered the password and then confirmed it, click on **Continue**.

![Master password](/subwallet-imgs/subwallet-3.png)

Now you will be shown a seed phrase together with the option to back it up. Once you have saved and stored it in a safe place, choose **I have kept it somewhere safe**.

![Create new seed phrase](/subwallet-imgs/subwallet-4.png)

!!! Caution
    You should never share your seed phrase (mnemonic) or private key with anyone. This gives them direct access to your funds.

You have finished creating a new account! If you want to create additional accounts, follow these steps:
1. Choose the accounts tab on the top of the extension.

![Create additional accounts 1](/subwallet-imgs/subwallet-5.png)

2. Click on **Create a new account** and repeat the steps above.

![Create additional accounts 2](/subwallet-imgs/subwallet-6.png)

### Import an existing account

To import an account that you have already created, choose **Import an account**. 

![SubWallet browser extension home screen](/subwallet-imgs/subwallet-7.png)

Then you can choose your preferred method of importing.

![Methods of importing](/subwallet-imgs/subwallet-8.png)

After you have chosen a method, you will be prompted to create a master password. Enter your password and click on **Continue**.

![Master password](/subwallet-imgs/subwallet-3.png)


!!! Caution
    Please note that SubWallet is non-custodial, so you would be the only person who knows your password; we cannot help you restore your password once it is lost. Please make sure that your password is well-kept.

#### Using seedphrase

You could choose between importing either a Substrate (Polkadot) account or EVM (Ethereum) account, or both. After choosing, click on **Import account**

![Methods of importing](/subwallet-imgs/subwallet-9.png)

Enter your seedphrase in the text boxes. You can use either a 12-word seedphrase or a 24-word seedphrase to import your account. Click on **Import account** and your account has been imported!

![Import using seedphrase](/subwallet-imgs/subwallet-10.png)

!!! Incompatibility
    In some cases, if you import an account from a seed phrase, problems can arise if the seed phrase of your original wallet is not compatible with SubWallet. **Trust Wallet** and **Safepal** are among the wallets not compatible with us. 

#### Using Polkadot.js JSON file

You can import a Polkadot.js account after exporting the JSON backup file. Click on the **Import from Polkadot.js** field to upload a file from your device, or drag and drop your JSON file into the field.

![Upload JSON file](/subwallet-imgs/subwallet-11.png)

You will then need to enter your JSON file password (created when you set up the wallet for the first time) and click **Import by JSON file**. 

![JSON file password](/subwallet-imgs/subwallet-12.png)

!!! Note
    If you want to import multiple accounts simultaneously from a JSON file, you are required to enter the password for each account you want to import.

#### Using MetaMask private key

Once you have exported your private key, enter it into the text box then click on **Import account**.

![Import with private key](/subwallet-imgs/subwallet-13.png)

#### Using QR code

![Import with QR Code](/subwallet-imgs/subwallet-14.png)

Click on **Scan QR**. If you have not enabled camera access yet, a message will show up prompting you to **Go to settings**. 

![Enable camera access](/subwallet-imgs/subwallet-15.png)

On the settings page, toggle on **Camera access for QR** then head back to the QR page, click on **Scan QR**, and scan your accounts' QR code. After the successful import of your account by QR code, you will be directed to the Homepage. 

#### Import additional accounts

You have finished importing your account! If you want to import additional accounts, follow these steps:
1. Choose the accounts tab on the top of the extension.

![Create additional accounts 1](/subwallet-imgs/subwallet-5.png)

2. Click on the **Import** icon and repeat the steps above.

![Create additional accounts 2](/subwallet-imgs/subwallet-16.png)

## Interacting with StellaSwap

### Connect to StellaSwap

To connect your account to StellaSwap, choose **Manage tokens** on the home screen. It is placed under all of the displayed tokens.

![Manage tokens](/subwallet-imgs/subwallet-17.png)

On the search bar, search for **STELLA**. Toggle on the tokens to enable them.

![Enable Stella](/subwallet-imgs/subwallet-18.png)

Head back to the home screen. You should be able to see that StellaSwap tokens have been enabled.

![Connected StellaSwap](/subwallet-imgs/subwallet-19.png)

## Receive token

From your home screen, choose the first blue icon under the eye. 

![Receive](/subwallet-imgs/subwallet-20.png)

!!! If you are in all-accounts mode

    You will be prompted to choose an account if you are in all-accounts mode.
    ![All accounts mode](/subwallet-imgs/subwallet-21.png)

Search for the token that you would like to receive, in this case, STELLA. You can either **Copy the address** or **View address QR**.

![Copy address](/subwallet-imgs/subwallet-22.png)


<!-- !!! Note
    ASTR is allowed to execute cross-chain transfer, so when choosing the token, make sure you are receiving ASTR on the correct chain by checking the network icon under the tokens.
    ![Cross-chain receive](/subwallet-imgs/subwallet-30.png) -->

Send the address or show the QR code to the sender and you'll be able to receive STELLA from them!

![QR code](/subwallet-imgs/subwallet-23.png)

### Send a transaction

To get started with a simple token transfer to another address, you can click the send icon.

![Send transaction](/subwallet-imgs/subwallet-24.png)

Next, you can take the following steps:

1. Specify the asset to send and the destination chain. 

    !!! Note 
        STELLA is a token on Moonbeam, so you will also need to have GLMR in your accont for the transaction fee.

2. Enter the destination address
3. Enter the amount of tokens to send
4. Look over the transaction details, then press **Transfer**

![Transaction details](/subwallet-imgs/subwallet-25.png)

On the next screen, you can review the transaction details and submit the transaction. If the transaction details look good, you can click **Approve** to send the transaction.

![Approve transaction](/subwallet-imgs/subwallet-26.png)

After you send the transaction, you will be able to review the transaction details.

### Connect to the StellaSwap dApp

First, head to the [StellaSwap dApp](https://app.stellaswap.com/exchange/swap). 

![StellaSwap](/subwallet-imgs/subwallet-27.png)

To connect your wallet to StellaSwap, click on **Connect to a wallet** then choose SubWallet.

![Conenct wallet](/subwallet-imgs/subwallet-28.png)

A window will appear. Choose the account that you would like to connect then choose **Connect**. Approve the connection and you have successfully connected to the StellaSwap dApp!

![Choose accounts](/subwallet-imgs/subwallet-29.png)