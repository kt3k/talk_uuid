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
class: middle
- 個人的にはいらない機能
- Champion: Ben Coe さんにはもっと別なことをやって欲しい
---
class: middle, center
Fin
