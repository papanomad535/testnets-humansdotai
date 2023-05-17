
2:40PM INF service stop impl={"Logger":{}} module=consensus msg={} server=node
2:40PM INF service stop impl={"Logger":{}} module=consensus msg={} server=node wal=/home/fric/.humansd/data/cs.wal/wal
2:40PM ERR Won't start a peer - switch is not running module=p2p peer={"Data":{},"Logger":{}} server=node
2:40PM INF service stop impl={"Dir":"/home/fric/.humansd/data/cs.wal","Head":{"ID":"swOQhtmv9KPg:/home/fric/.humansd/data/cs.wal/wal","Path":"/home/fric/.humansd/data/cs.wal/wal"},"ID":"group:swOQhtmv9KPg:/home/fric/.humansd/data/cs.wal/wal","Logger":{}} module=consensus msg={} server=node wal=/home/fric/.humansd/data/cs.wal/wal
2:40PM INF service stop impl={"Logger":{},"Switch":{"Logger":{}}} module=evidence msg={} server=node
2:40PM INF service stop impl={"Logger":{},"Switch":{"Logger":{}}} module=statesync msg={} server=node
2:40PM INF service stop impl={"Logger":{},"Switch":{"Logger":{}}} module=pex msg={} server=node
2:40PM INF service stop book=/home/fric/.humansd/config/addrbook.json impl={"Logger":{}} module=p2p msg={} server=node
2:40PM ERR Stopped accept routine, as transport is closed module=p2p numPeers=0 server=node
2:40PM INF Saving AddrBook to file book=/home/fric/.humansd/config/addrbook.json module=p2p server=node size=119
2:40PM INF Closing rpc listener listener={"Listener":{}} server=node
2:40PM INF RPC HTTP server stopped err="accept tcp [::]:26657: use of closed network connection" module=rpc-server server=node
2:40PM ERR Error serving server err="accept tcp [::]:26657: use of closed network connection" server=node
Started humans Node Service.
2:42PM INF Unlocking keyring
2:42PM INF starting ABCI with Tendermint
2:42PM INF starting node with ABCI Tendermint in-process
2:42PM INF service start impl=multiAppConn module=proxy msg={} server=node
2:42PM INF service start connection=query impl=localClient module=abci-client msg={} server=node
2:42PM INF service start connection=snapshot impl=localClient module=abci-client msg={} server=node
2:42PM INF service start connection=mempool impl=localClient module=abci-client msg={} server=node
2:42PM INF service start connection=consensus impl=localClient module=abci-client msg={} server=node
2:42PM INF service start impl=EventBus module=events msg={} server=node
2:42PM INF service start impl=PubSub module=pubsub msg={} server=node
2:42PM INF service start impl=IndexerService module=txindex msg={} server=node
2:42PM INF ABCI Handshake App Info hash="���'�ݴ�|<�!(�43l'��G��V�\x1e3p�\x16I�" height=87721 module=consensus protocol-version=0 server=node software-version=0.2.1
2:42PM INF ABCI Replay Blocks appHeight=87721 module=consensus server=node stateHeight=87721 storeHeight=87721
2:42PM INF Completed ABCI Handshake - CometBFT and App are synced appHash="���'�ݴ�|<�!(�43l'��G��V�\x1e3p�\x16I�" appHeight=87721 module=consensus server=node
2:42PM INF Version info abci=0.17.0 block=11 cmtbft_version=0.34.27 commit_hash= p2p=8 server=node
2:42PM INF This node is a validator addr=60DFB17EB8F8E368BBC77597A4A94B1D689F75A2 module=consensus pubKey=Lp6Jkj4vaolBezx6lMgrymEDyrq9qXscziW/cYVJ9Sg= server=node






2:48PM INF Closing rpc listener listener={"Listener":{}} server=node
2:48PM INF RPC HTTP server stopped err="accept tcp [::]:26657: use of closed network connection" module=rpc-server server=node
2:48PM ERR Error serving server err="accept tcp [::]:26657: use of closed network connection" server=node
humansd.service: Deactivated successfully.
Stopped humans Node Service.
humansd.service: Consumed 1min 6.626s CPU time.
Started humans Node Service.
2:49PM INF Unlocking keyring
2:49PM INF starting ABCI with Tendermint
2:49PM INF starting node with ABCI Tendermint in-process
2:49PM INF service start impl=multiAppConn module=proxy msg={} server=node
2:49PM INF service start connection=query impl=localClient module=abci-client msg={} server=node
2:49PM INF service start connection=snapshot impl=localClient module=abci-client msg={} server=node
2:49PM INF service start connection=mempool impl=localClient module=abci-client msg={} server=node
2:49PM INF service start connection=consensus impl=localClient module=abci-client msg={} server=node
2:49PM INF service start impl=EventBus module=events msg={} server=node
2:49PM INF service start impl=PubSub module=pubsub msg={} server=node
2:49PM INF service start impl=IndexerService module=txindex msg={} server=node
2:49PM INF ABCI Handshake App Info hash="p�ۈ_��\x16\x0eۯ�a�)�\x17�_�GȲӢ)Ԇ�==�" height=87800 module=consensus protocol-version=0 server=node software-version=0.2.1
2:49PM INF ABCI Replay Blocks appHeight=87800 module=consensus server=node stateHeight=87800 storeHeight=87800
2:49PM INF Completed ABCI Handshake - CometBFT and App are synced appHash="p�ۈ_��\x16\x0eۯ�a�)�\x17�_�GȲӢ)Ԇ�==�" appHeight=87800 module=consensus server=node







2:50PM ERR Error stopping pool err="already stopped" module=blockchain server=node
2:50PM ERR Stopped accept routine, as transport is closed module=p2p numPeers=0 server=node
2:50PM INF Closing rpc listener listener={"Listener":{}} server=node
2:50PM INF RPC HTTP server stopped err="accept tcp [::]:26657: use of closed network connection" module=rpc-server server=node
2:50PM ERR Error serving server err="accept tcp [::]:26657: use of closed network connection" server=node
humansd.service: Deactivated successfully.
Stopped humans Node Service.
humansd.service: Consumed 13.896s CPU time.
