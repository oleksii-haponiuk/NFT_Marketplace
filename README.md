# NFT_Marketplace

Testing: https://tundra-keeper-3d2.notion.site/NFT_Marketplace-unit-testing-a7fc612951ed41f9a8e6131f6b6c54a5 (Notion)

Possible vector of attack:
- Anybody can remove NFT from the market even if they don't own it.

Things to note:
- There's no way to get list of available tokens. It should be stored externally. External list could be verified with `getAvailable` function.
