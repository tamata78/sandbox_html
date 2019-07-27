# xpath

|xpath|説明|
|:-|:-|
|//a|全ての<a> ノード|
|(//a)[1]|全ての<a> ノードを取得して、最初の１個|
|//a/span|span ノードで、親が<a>のものをすべて|
|//a/@href|aノードのすべてのhref属性|
|//a/text()|aノードのすべてのtext()表現|
|//a[@href="/index.html"]|aノードのうち href属性が"/index.html"と合致するモノすべて|
|//a[contains(@href,"index.html")]|aノードのうち href属性に index.html を含むものすべて|
|//title | //meta|title と meta タグを両方|
|//img/@alt | //img/@alt|img@alt と img@src を複数同時に|
|//img[ contains(@src,'jpg') or contains(@src,'png')]|img ノードで src に jpg/pngを含むものすべて|
|//div/*|div の子要素すべて|
|//div//*|div の子孫要素をすべて|
|id("tid123")/following-sibling::div|#tid123に隣接する div|
|//tbody//tr[ position() > 2 ]|tbody中のtrで３番目以降もの（Range:範囲指定)|

