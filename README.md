# Yeahreum Daemon Windows server Command

 How do I setup a Yeahreum Daemon Windows Command (YDWS) on Windows Server 2019 |  2018 | 2015


 Download the Windows QT wallet from yeahreum and upload the file to your Windows Server.

 # Note: replace “yeahreum”


 Extract the zip file [Download GT YDWS](https://api.server.yeahreum.net/daemon/wserver/yeahreum.exe) 
 
 [Download Yahrm Daemon ](https://api.server.yeahreum.net/daemon/wserver/yeahreumd.exe) 


 Close your wallet and create the file yeahreum.conf in the folder
 
 ```
 “%APPDATA%\yeahreum\”.
```

 # Paste the following lines in yeahreum.conf.

```
 rpcuser=rpc_yeahreum
 rpcpassword=7c6ca5196c481b88011a6bcea
 rpcallowip=127.0.0.1
 rpcport=10037
 listen=1
 server=1
 addnode=yahrm.net
```

# Start your YDWS with the following command.

```
Your wallet will function as a node when you start your wallet. (open Yeahreum Wallet)
```

# For your [Ubuntu machine](https://github.com/yeahreum/daemon)
