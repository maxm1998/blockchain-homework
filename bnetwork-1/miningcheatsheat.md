account 1 key address :  0x723864fE015c47Ed5198D2F7C74F3B026364d400
Password: Marubos18

account 2 key address: 0x32e071a4BaaA0F68721a57E20Cea134016d6975E
password: Marubos123


## Mining cheat sheat:

### Running Node1

./geth --datadir node1 --unlock 0x723864fE015c47Ed5198D2F7C74F3B026364d400 --mine --rpc --allow-insecure-unlock

Node1 enode address: 

enode://9768fe00fc136878ed47e09674022c68d8e119741d08b0a8da131ffcaabe982cb4c4a416407f64a2ff5574298a9de5d57405efb3951ab653493fdb53c8c9a3f1@127.0.0.1:30303

### Running Node2

./geth --datadir node2 --unlock 0x32e071a4BaaA0F68721a57E20Cea134016d6975E --mine --port 30304 --bootnodes enode://9768fe00fc136878ed47e09674022c68d8e119741d08b0a8da131ffcaabe982cb4c4a416407f64a2ff5574298a9de5d57405efb3951ab653493fdb53c8c9a3f1@127.0.0.1:30303 --ipcdisable --allow-insecure-unlock

