# Argon Multi-Chain Security & Token Inspector SDK (Solana SPL + EVM)

Lightweight, zero-dependency Python SDK & CLI for inspecting **Solana SPL Token Mint/Freeze Authorities** (`getAccountInfo` `jsonParsed`) and **EVM Smart Contract Proxy Slots**.

## Live Self-Test Output (Solana Mainnet USDC Mint)
```json
{
  "status": "OK",
  "network": "solana-mainnet",
  "mint_address": "EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v",
  "decimals": 6,
  "raw_supply": "7844950340205094",
  "mint_authority": "BJE5MMbqXjVwjAF7oxwPYXnTXDyspzZyt4vwenNw5ruG",
  "freeze_authority": "7dGbd2QZcCKcTndnHcTL8q7SMVXAkp688NTQYwrRCrar",
  "is_initialized": true,
  "security_flags": [
    "ACTIVE_MINT_AUTHORITY_CAN_INFLATE_SUPPLY",
    "ACTIVE_FREEZE_AUTHORITY_CAN_FREEZE_ACCOUNTS"
  ],
  "risk_score_0_to_100": 75
}
```

## License
MIT License
