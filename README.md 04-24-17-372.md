# Sofamon Subgraph

**Summary:** Approval, Transfer, and Level info of Sofamon NFT, written in ERC-721 format

**Slug:** sofamon-subgraph

**Network:** Goreli Testnet

**Contract address:** 0x149b888374622a1126Af05d5eB746502679e0823

**Subgraph endpoints:** https://api.studio.thegraph.com/query/41437/sofamon-subgraph/v0.0.1


Simple Query using Curl
```
curl 'https://api.studio.thegraph.com/query/41437/sofamon-subgraph/v0.0.1' \
  -X POST \
  -H 'content-type: application/json' \
  --data '{"query": "{ setLevels { level nftId } }" }'
```
