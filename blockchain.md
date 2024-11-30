# Check if the rpc is working or not 
```
curl -X POST \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","method":"eth_blockNumber","params":[],"id":1}' \
 https://eth.llamarpc.com
```
result will be in format:-
```
{"jsonrpc":"2.0","id":1,"result":"0x144e3ad"}
```

The command `history | grep validator` will display all the commands typed with the word 'validator'.
Your private key will be displayed in the results
