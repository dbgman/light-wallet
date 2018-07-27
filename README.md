# Light-wallet
### web wallet in a box - Dont expose this to the internet or you'll lose everything.

![image]()
--

Start up walletd and Lumeneocoind:

`./walletd -w YOURWALLET.wallet -p YOURPASSWORD --rpc-password test --daemon-address 127.0.0.1 --enable-cors "*"`

If you want to change the RPC password, set it in the config.js file.

Make sure you are using a version of walletd that supports the --enable-cors arg, launch walletd with --help to verify.
