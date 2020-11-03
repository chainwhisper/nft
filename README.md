## NFT MetaData

[EIP-721 2](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md) includes an optional **metadata extension** with a `name`, `symbol` and for each tokenID a `tokenURI` with can point to a JSON file with `name`, `description` and `image` for the given token ID.

For testing purpose, we can use [My JSON Server 6](https://my-json-server.typicode.com/) where we can store a single JSON file in a GitHub repository that we can access via a fake JSON server.

![:warning:](https://sjc3.discourse-cdn.com/business6/images/emoji/twitter/warning.png?v=9) For production we need to store our metadata in a permanent location that can exist for the life of the token.

For images we will use twemoji Graphics from [twitter/twemoji 2](https://github.com/twitter/twemoji) which are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

A sample JSON for tokenID 0 is:
[http://my-json-server.typicode.com/abcoathup/samplenft/tokens/0 8](http://my-json-server.typicode.com/abcoathup/samplenft/tokens/0)
