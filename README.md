# Hayalet Sevgilim Şarkı Sözleri

## İçerik

```
Ceza mı bu
Çektiğim çile mi
Yıllardır tuttuğum nöbet bitmeyecek mi?
Bir küçük kar tanesi gibiyim
Avucunda eriyen dön bebeğim

Gözyaşlarını görürsem
Erir kanatlarım
Uçamam rüyalarında yanına
Sonsuzluk senle başladı
O küçük dünyamda
Unutma gittiğinde yarım kaldım

Çöllerdeyim yanıyorum
Kutuptayım üşüyorum
Ceza benim çekiyorum ne olur dön
Uzanıyorum tutamıyorum
Özlüyorum ağlıyorum
Yasak mısın anlamıyorum ne olur dön

Sevmesen de beni özledim sesini
Git desem de yine gitmesen
Yıllardır çektiğim bu hasret mi çile mi?
Haram mısın bana bi' bilsem

Sevmesen de beni özledim sesini
Git desem de yine gitmesen
Yıllardır çektiğim bu hasret mi çile mi?
Haram mısın bana bi' bilsem

Bebeğim benim, hayalet sevgilim
Bebeğim benim, hayalet sevgilim

Hayalet sevgilim

Çöllerdeyim yanıyorum
Kutuptayım üşüyorum
Ceza benim çekiyorum ne olur dön
Uzanıyorum tutamıyorum
Özlüyorum ağlıyorum
Yasak mısın anlamıyorum ne olur dön

Sevmesen de beni özledim sesini
Git desem de yine gitmesen
Yıllardır çektiğim bu hasret mi çile mi?
Haram mısın bana bi' bilsem

Sevmesen de beni özledim sesini
Git desem de yine gitmesen
Yıllardır çektiğim bu hasret mi çile mi?
Haram mısın bana bi' bilsem

Bebeğim benim hayalet sevgilim
Bebeğim benim hayalet sevgilim

Hayalet sevgilim
Hayalet sevgilim
```

## Neden

Baktım GitHub "popülerlik" kriterleri koymaya başlamış, bunlar üzerinden
kullanıcıları ve katkıları ayrımlamaya başlamış. O halde ben de popülizmin
dibine vurmak istedim. Buyrun, Sözleri
[İrem Aydın](https://twitter.com/iremyagciaydin)'a ait olan Hayalet Sevgilim.
Bugüne kadar topluluk yararını gözettiğini düşündüğüm GitHub, bu repoyu
starlarsanız belki seneye beni de sevgili popüler kullanıcılar listesine alır 🙏
Lütfen alsın çünkü.

Aslında bunu Twitter'dan bas bas duyurmam, GitHub'da popüler repolara girdikten
sonra gifler alıp yine Twitter'da dolaşıma sokmam, YouTube'da videosunu çekip
sonra bu videoyu buraya linklemem filan gerekli daha fazla star alması için. Ama
onu sizler için 100 star'dan sonra yapacağım. Çünkü klik ekonomisi böyle
çalışıyor.

## Programatik Kullanım

Deno / Web / ES Modules:

```js
import data from "https://raw.githubusercontent.com/eserozvataf/hayalet-sevgilim-sarki-sozleri/master/js/index.json" assert {
  type: "json",
};
// console.log(data);
```

veya

```js
import data from "https://raw.githubusercontent.com/eserozvataf/hayalet-sevgilim-sarki-sozleri/master/js/mod.js";
// console.log(data);
```

Node.js:

```js
const data = require("./index.json");
// console.log(data);
```

Shell:

```bash
data=$(curl https://raw.githubusercontent.com/eserozvataf/hayalet-sevgilim-sarki-sozleri/master/js/index.json)
# echo $data
```

Python I:

```bash
cd ./py
python3 program.py
```

Python II:

```bash
cd ./python
make || make run || uvicorn main:app --reload
```

Swift:

```bash
cd ./hayalet-sevgilim-sarki-sozleri/swift/HayaletSevgilim-CommandLine
swift run
```

PHP:

```php
<?php

use HayaletSevgilim\HayaletSevgilim;

HayaletSevgilim::print();
```

GO I:

```go
import "github.com/eserozvataf/hayalet-sevgilim-sarki-sozleri/go/hayaletsevgilim"

hayaletsevgilim.Print();
```

PowerShell:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
$result = Invoke-WebRequest -UseBasicParsing -Uri "https://raw.githubusercontent.com/eserozvataf/hayalet-sevgilim-sarki-sozleri/master/js/index.json"

if ($result.StatusCode -eq 200)
{
    $lyrics = ConvertFrom-Json $result.Content
    Write-Output $lyrics
}
```

Rust I:

```bash
cd ./rust
cargo build
cargo run
```

Rust II:

```bash
cd ./rs
cargo build
cargo run
```

GO I:

```bash
cd ./go
go run .
```

GO II:

```bash
cd ./golang
go run .
```

C:

```bash
gcc main.c

./a.out
```

Asm:

```bash
cd  ./Asm
make
./hs
```

Dart:

```dart
import 'HayaletSevgilim.dart';

HayaletSevgilim.printLyrics();
```

SQL:

```bash
# remote:
mysql -u root -p -e "$(curl https://raw.githubusercontent.com/eserozvataf/hayalet-sevgilim-sarki-sozleri/master/sql/hayalet-sevgilim.sql)"

# local:
mysql -u root -p -e "$(cat sql/hayalet-sevgilim.sql)"
```

Elixir:

```bash
cd ./elixir

elixir main.exs
```

Lua:

```bash
lua ./lua/main.lua
```

CSS:

```html
<link rel="stylesheet" href="hayalet_sevgilim.css" />
```

Brainfuck:

```bash
brainfuck ./brainfuck/main.bf
```

Bash:

```bash
chmod +x ./bash/hayalet_sevgilim.sh
./bash/hayalet_sevgilim.sh
```

Perl:

```bash
perl ./perl/hayalet_sevgilim.pl
```

Emacs-lis:

```bash
emacs --load ./emacs-lisp/hayalet_sevgilim.el
```

Erlang:

```bash
cd ./erlang
erl
c(hayalet_sevgilim).
hayalet_sevgilim:print().
```

Scala:

```bash
cd ./scala
scalac main.scala
```

Nginx Web Server in Docker Container:

```bash
docker build -t hayalet-sevgilim-sarki-sozleri .
..
docker run --name hayalet-sevgilim-sarki-sozleri -p 80:80 hayalet-sevgilim-sarki-sozleri
```

iOS App:

<img src="./screenshots/ios/ios3.png" width="300" />
<img src="./screenshots/ios/ios1.png" width="300" />
<img src="./screenshots/ios/ios2.png" width="300" />
```
OPEN XCODE AND JUST RUN
```

Haskell:

```bash
nix run
```

## Programlama Dilleri

- [Asm](./Asm/)
- [Bash](./bash)
- [Brainfuck](./brainfuck/)
- [C](./C/)
- [C++](./cpp/)
- [C#](./csharp/)
- [CSS](./css/)
- [Dart](./dart/)
- [Elixir](./elixir/)
- [Emacs Lisp](./emacs-lisp/)
- [Erlang](./erlang/)
- [Go I](./go/)
- [Go II](./golang/)
- [Haskell](./haskell/)
- [iOS/Swift](./ios/)
- [Java](./java/)
- [JavaScript](./js/)
- [LOLCODE](./lolcode/)
- [Lua](./lua/)
- [Perl](./perl/)
- [PHP](./php/)
- [Python I](./py/)
- [Python II](./python/)
- [Ruby](./ruby/)
- [Rust I](./rust/)
- [Rust II](./rs/)
- [Solidity](./sol/)
- [Shell Script](README.md)
- [SQL](./sql/)
- [Swift](./swift/)
- [TypeScript](./ts/)
- [Scala](./scala/)

## Kütüphaneler

- [AngularJS](./library/angularjs/)

## Farklı Formatlar

- [Binary](./binaryToAscii/)
- [HTML](./html/)
- [JSON](./js/)
- [Open Office](./ODT/)
- [SVG](./svg/)
- [tex](./tex/)
- [tree](./tree/)
- [XML](./xml/)
- [YAML](./yaml/)

## Arabirimler

- [ios](./ios/)
- [ui](./ui/)

## Yol Haritası

- PHP, Ruby gibi diğer kalan diller için de modüller oluşturulabilir.

## Lisans

Apache-2.0
