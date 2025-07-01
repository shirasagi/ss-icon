SHIRASAGI Icon Font
===

# BUILD

次のコマンドを実行してください。

~~~
yarn install
yarn build
~~~

dist/assets/font ディレクトリ以下に次の成果物が作成されます。

- shirasagi-icons.eot: フォントファイルです。シラサギの public/assets/font/ 以下へコピーします。
- shirasagi-icons.woff: フォントファイルです。シラサギの public/assets/font/ 以下へコピーします。
- shirasagi-icons.woff2: フォントファイルです。シラサギの public/assets/font/ 以下へコピーします。
- shirasagi-icons.css/shirasagi-icons.scss: フォントを表示するためのCSSです。app/assets/stylesheets/ss/ 以下へコピーし、style.scss に組み込みます。
- shirasagi-icons.html: フォントのプレビューです。ブラウザで開くとフォントが表示されますが、正しく表示するにはshirasagi-icons.cssのフォントファイルのパスを調整する必要があります。

# SVG Specs

- viewBox は "0 0 32 32" です。必ずこの viewBox にしてください。
- SVGを幅: 128px、高さ: 128pxで表示した際に十分に奇麗であれば問題ないです。pathの制御点を可能な限り減らすようにしてください。
