# LOVE FOR PEACE — Permanent Archive

> A commemorative NFT project, released to the public and given to the chain.

---

## ⚠️ Disclaimer

LOVE FOR PEACE is an independent, non-commercial fan art project created purely as a commemorative tribute. It is **not affiliated with, endorsed by, or connected to** any official organization, company, individual, or token project. The creator receives **no profit** from this collection — every mint permanently burns LOVE tokens, and **no royalties or earnings are collected**. This is **not financial advice** and **not a solicitation** to buy anything. Created with the wish for peace.

---

## 1. Contract

| Field | Value |
|---|---|
| Network | Ethereum Mainnet |
| Standard | ERC-1155 |
| Contract Address | `0x8dd9030ffce8a003fb81e17dec3c7475548107ee` |
| Etherscan | https://etherscan.io/address/0x8dd9030ffce8a003fb81e17dec3c7475548107ee |
| OpenSea | https://opensea.io/collection/0x8dd9030ffce8a003fb81e17dec3c7475548107ee |
| Ownership | Renounced — owner is `0x0`, no one can control the contract |

**Mint mechanism:** Each mint permanently burns 100 LOVE to the dead address `0x...dEaD`, in exchange for one random box.

---

## 2. Collection

100 unique designs across five rarity tiers.

| Token IDs | Rarity | Count | Max Supply each |
|---|---|---|---|
| 1 | Legendary | 1 | 1 (owner-reserved) |
| 2–10 | Ultra Rare | 9 | 10 |
| 11–30 | Rare | 20 | 20 |
| 31–55 | Uncommon | 25 | 50 |
| 56–100 | Common | 45 | 100 |

Metadata mapping is direct: token ID `N` -> file `00N.json` (zero-padded to 3 digits).

---

## 3. IPFS Content IDs (CIDs)

These CIDs are content fingerprints. They are safe to share publicly and cannot be tampered with — any change to the content produces a different CID.

| Content | CID |
|---|---|
| **Artwork images** | `bafybeiewjjv2lzace7lryhcyzrootocb26gj52pneocnwllrgembc6w4cu` |
| **Revealed metadata** (on-chain baseURI) | `bafybeig7lkg3jktlqfs4izkz52uti2cwuzshtvvgamhlzxdlct5ey5tcue` |
| **Mystery box metadata** (unrevealedURI) | `bafkreigigdzsxilu7q2bfsycuhkxl3xxvjqxrhtdplaj3px6xoivldr5ne` |

The artwork CID is the heart of this project — these are the original pieces.

---

## 4. How to Verify

Open any of these in a browser (via a public IPFS gateway):

```
https://ipfs.io/ipfs/bafybeig7lkg3jktlqfs4izkz52uti2cwuzshtvvgamhlzxdlct5ey5tcue/001.json
https://ipfs.io/ipfs/bafybeiewjjv2lzace7lryhcyzrootocb26gj52pneocnwllrgembc6w4cu/
```

The first returns the metadata for token #001 (the Legendary piece); the second lists all artwork images. You can confirm the on-chain `baseURI` matches by reading the contract on Etherscan.

---

## 5. How to Preserve

This project's survival no longer depends on any single service. **Anyone who loves it can help keep it alive.**

### Option A — Pin on IPFS

If you run an IPFS node:

```bash
ipfs pin add bafybeiewjjv2lzace7lryhcyzrootocb26gj52pneocnwllrgembc6w4cu
ipfs pin add bafybeig7lkg3jktlqfs4izkz52uti2cwuzshtvvgamhlzxdlct5ey5tcue
ipfs pin add bafkreigigdzsxilu7q2bfsycuhkxl3xxvjqxrhtdplaj3px6xoivldr5ne
```

Once pinned on your node, the content lives on as long as your node is online.

### Option B — Free pinning services

Paste the CIDs above into any free IPFS pinning service (e.g. Pinata, web3.storage, Filebase) to keep a copy alive without running your own node.

### Option C — Download a local backup

Download the full offline archive (all 100 images + all metadata) and keep it on your own drive:

> **[Archive download link — to be filled in]**
> (e.g. GitHub release, Arweave, or any permanent storage)

For truly permanent storage, consider uploading the archive to **Arweave** (pay once, stored forever) — a natural fit for a commemorative project.

---

## 6. Why This Exists

This is a personal tribute, made with a wish for peace. It earns nothing, controls nothing, and asks for nothing. The contract is ownerless; the art is free to keep, copy, and preserve. If it brings you a moment of peace, it has done its work.

*— Created with the wish for peace.*
