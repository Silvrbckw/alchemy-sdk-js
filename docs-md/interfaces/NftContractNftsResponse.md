[alchemy-sdk](../README.md) / [Exports](../modules.md) / NftContractNftsResponse

# Interface: NftContractNftsResponse

The response object for the [getNftsForContract](../classes/NftNamespace.md#getnftsforcontract) function. The object
contains the NFTs with metadata inside the NFT contract.

## Table of contents

### Properties

- [nfts](NftContractNftsResponse.md#nfts)
- [pageKey](NftContractNftsResponse.md#pagekey)

## Properties

### nfts

• **nfts**: [`Nft`](Nft.md)[]

An array of NFTs with metadata.

#### Defined in

[src/types/types.ts:1624](https://github.com/alchemyplatform/alchemy-sdk-js/blob/f2b072e/src/types/types.ts#L1624)

___

### pageKey

• `Optional` **pageKey**: `string`

Pagination token that can be passed into another request to fetch the next
NFTs. If there is no page key, then there are no more NFTs to fetch.

#### Defined in

[src/types/types.ts:1630](https://github.com/alchemyplatform/alchemy-sdk-js/blob/f2b072e/src/types/types.ts#L1630)
