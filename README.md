2021年6月11日，成功运行

备注 ： 
rpc接口随后将改字段为 http  

执行命令 ：
nohup geth --goerli --datadir="$HOME/Goerli" --rpc --rpcaddr=0.0.0.0 --rpcport=8545 --ws --ws.addr=0.0.0.0  --ws.port=8546  --syncmode "light" &  
