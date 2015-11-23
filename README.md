# ninki-recover

Download this repository to recover your bitcoins from Ninki Wallet using the online and offline key phrases and your master public key.

Extract the downloaded zip file, run recover.html using Chrome browser

What you need:

* Your offline key phrase - a 12 word phrase (in older accounts this was 24 words and called cold key)
* Your online key phrase - a 12 word phrase (in older accounts this was 24 words and called hot key)
* Your master public key a long string beginning with xpub

***If pasting the phrases from a password manager, be careful not to paste extra characters at the end of the phrase.***

1. Enter your xpub and phrases
2. Click next
3. Click scan addresses
4. Wait until scan is complete (this may take some time depending on the number of transactions on the account)
6. check the balance is correct
7. Click Next
8. Enter a bitcoin address to recover the funds to.
9. Click claim funds
10. Make a note of the tx id for your reference

Note: this tool uses the chain.com API to lookup balances and broadcast the transaction
