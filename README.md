launch your stratum first in a terminal:

./duta-stratumd   --bind 0.0.0.0:12001   --daemon http://127.0.0.1:19085/   --share-bits 28   --network mainnet

start the miner in a other terminal:

./duta-stratum-miner --host IP_DU_STRATUM --port 12001 --address ADDRESS --gpu
