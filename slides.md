class: middle, center
# Proposal UUID
stage 0 -> 1 (Oct 2019)
---
class: middle, center
# 要は
---
class: middle, center
# UUID が使える
---
class: middle, center, inverse
# 完
---
class: middle, center
以下 補足説明
---
class: middle, center
# 文法
---
# 文法
- 2パターン検討されている

Global
```js
const uuid = UUID() // => "52e6953d-edbe-4953-be2e-65ed3836b2f0"
```
Module
```js
import uuid from 'std:uuid'
const id = uuid() // => "52e6953d-edbe-4953-be2e-65ed3836b2f0"
```
---
# 細かい補足
- とりあえず UUID v4 (完全にランダムな奴) だけ実装する想定をしている
- ほとんどのユースケースで v4 が使われているから (89.5%)
- 2位以下は v1 (9.7%), v5 (0.8%), v3 (0.1%)
---
class: middle, center
# 個人的な見解
---
# 個人的な見解
- いらない気がする
- 言語に入っている必要がない
- UUID が入るなら他にいくらでも入って良さそうなものがある => これをやりだしたらきりがないのではないか
- 誰も npm の uuid で困っていない
---
蛇足
- Champion の Ben Coe さんは nyc や istanbul の作者/メンテナ
- v8 のカバレッジ機能を使った c8 を作ったり, カバレッジ界の王
- こんなどうでも良い機能の Champion をやるぐらいなら, もっとカバレッジ周りの仕事にフォーカスしてほしい
- => そう, たとえば, c8 の Deno サポートとか!
---
class: middle, center
ご清聴ありがとうございました 🙏
