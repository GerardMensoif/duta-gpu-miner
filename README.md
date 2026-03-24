launch the stratum first in a terminal: (https://github.com/dutagoproject/stratum)

./duta-stratumd   --bind 0.0.0.0:12001   --daemon http://127.0.0.1:19085/   --share-bits 28   --network mainnet

start the miner in a other terminal:

./duta-stratum-miner --host STRATUM_IP --port 12001 --address ADDRESS

If error: "error while loading shared libraries: libcudart.so.12: cannot open shared": 

sudo apt install libcudart12

You can run multiple miner on the same stratum

0% fees
