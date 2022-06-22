# goo-cli
CLI interface for the [goo.ne.jp](https://dictionary.goo.ne.jp/) online dictionary

If any html tags show up in the output, just let me know and I'll look into it

## Dependencies
- curl
- grep
- sed
- awk
- coreutils

## Usage:
```sh
./goo [word]
```

Example:
```sh
~/git/goo-cli $ ./goo 便利
べん‐り【便利】
［名・形動］
１ 目的を果たすのに都合のよいこと。あることをするのに重宝で、役に立つこと。また、そのさま。「生活するのに―な所」「―な調理器具」「地下鉄ができて―になった」
２ あることをする都合やぐあい。「買い物の―が悪い」
３ 大小便。通じ。
「大小の―の不浄を出して」〈今昔・一・四〉
```
