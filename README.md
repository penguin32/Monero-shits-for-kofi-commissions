# Monero-shits-for-kofi-commissions
public address be updated here with its gpg, to be verified by the commissioners

Because of text limiting shit from site, let me elaborate shit here.



For Nsfw commissioners, because of Visa/Mastercard bs, I'm relying on monero, if you're sfw commissioners you're safe to use Kofi/Paypal,

Instructions for Nsfw commissioners:
to verify the Monero address that I've sent, its best to verify it using my public gpg signature.

1. to do so, start by importing my public gpg block from this website.
if you're linux user, just run this command:
curl -sSL https://github.com/penguin32.gpg | gpg --import

if you're a windows loser, just download that penguin32.gpg,
note: you can see my github profile by just removing the suffix '.gpg' from that url
to verify its me.

2. to further verify that public gpg that you've imported, run this:
gpg --fingerprint johnmarvinpangilinan258@gmail.com
you should see this 6096 2B28 .... 957A E37E
ifSame=itsCorrect!


3. After you verified my public gpg, you can download the monero-address txt file and its monero-address gpg file to verify the address you'd sent money to.
the links of those files from:
github.com/penguin32/Monero-shits-for-kofi-commissions/blob/main/kofi-monero-address.txt
download those two files, then run
4. gpg --verify kofi-monero-address.txt.gpg
note: those two file should be at the same directory, I think.... *shrug shoulders*


it should show the signature to be valid if it matches the expected public key, 
if it not, then the Monero address has been tampered! which I don't recommend you sending money to that shit.
