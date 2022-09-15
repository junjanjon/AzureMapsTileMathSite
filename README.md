# AzureMapsTileMathSite

[ズーム レベルとタイル グリッド](https://docs.microsoft.com/ja-jp/azure/azure-maps/zoom-levels-and-tile-grid?tabs=typescript#tile-math-source-code
)のコードをサイトで動かす。

経度,緯度 <=> タイル <=> quadkey の相互変換ができます。

サイト: https://junjanjon.github.io/AzureMapsTileMathSite/index.html

# 参考

ズーム レベルとタイル グリッド: https://docs.microsoft.com/ja-jp/azure/azure-maps/zoom-levels-and-tile-grid?tabs=typescript#tile-math-source-code

# TileMath.ts のビルド

scripts/TileMath.ts を docs/scripts/TileMath.js にビルドする。

```sh
yarn install
yarn run tsc
```
