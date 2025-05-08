# Parallels tokens

A Unified repository containing optimized icons for token assets.

- Provides teams with ability to manage their token images
- Provides teams with ability to manage their token symbol and name

# Managing token images

## Allowed formats

### File formats

- PNG

  - MUST be a minimum of **400px x 400px** in size.
  - MUST only be placed in a chain root folder `/<chain>/tokens/<your-token-address>.png`
  - Should be Transparent.
  - Should have a circular or rounded edges (5px minimum) background if it is low contrast on dark background.

- SVG

  - SVG are only allowed as a reference if you are having trouble creating a PNG and want the team to help you.

### File Name formats

- Must be the fully qualified LOWERCASE **address** of the asset.
  - Note: Native ETH (or BNB/MATIC/FTM etc) should be `0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee`.png or .svg
- Must be in **lowercase** if the blockchain is case-insensitive (Ethereum-like chains).
- Must be in exact Check-summed case if blockchain is case-sensitive (Bitcoin-like or Tron-like chains)

## Submitting logos

1. Fork this repository.
2. Add logos in appropriate blockchain's directory
3. Commit your changes and open a **Pull Request** on this repository.
4. Tag someone to review and approve your submission.

### Managing cache

When changing a token image, you will need to clear the auto resized images from our cache.

1. Delete `/<chain>/tokens/<size>/<your-token-address>.png`
2. Repeat for all sizes
3. Commit your changes and open a **Pull Request** on this repository.
4. Tag someone to review and approve your submission.

### Rejections

Your submission will be straight away rejected if it does'nt conform to the [Allowed formats](#Allowed-formats).

.
