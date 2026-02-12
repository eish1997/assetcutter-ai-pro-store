# assetcutter-ai-pro-store

This repo hosts a **static JSON store** (GitHub Pages) for AssetCutter AI Pro.

## Structure

- `store/catalog.json`: store catalog (list of packs)
- `store/*.json`: pack files (each pack is a `PromptTemplate[]`)

## How to use (in AssetCutter AI Pro)

Set the Store Catalog URL to:

- `https://eish1997.github.io/assetcutter-ai-pro-store/store/catalog.json`

Then you can install/update packs from the in-app Store.

## Update a pack (remote update)

1. Edit a pack JSON under `store/` (add/modify templates).
2. Bump the `version` field in `store/catalog.json`.
3. Commit & push. GitHub Pages will serve the new JSON.

