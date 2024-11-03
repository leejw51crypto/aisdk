## aisdk cheatsheet

## run
- prepare two keys OPENAI_API_KEY, CRONOS_ZKEVM_TESTNET_API as env variables <- ai, explorer key
- git clone --recursive git@github.com:leejw51crypto/aisdk.git
- git submodule update --init --recursive <- already cloned?
- cd cdc-ai-agent-signer-app : yarn, yarn dev
- cd cryptocom-ai-agent-service : yarn, go.sh ,  query.sh is run ok, then good to go
- cd cryptocom-ai-agent-chatbot : yarn, go.sh ,   `get latest block` is run ok, then good to go
- cd cryptocom-ai-agent-pychatbot : python chat.py  <- pip install if needed
  
## prompts
- get latest block
- send 0x...receiver 1.0 to erc20 0x..erc20contract 
- send 0x...receiver 0.1
  