title=Hugoにgoogle analyticsを導入する
slug=hugo-ga
tags=[google analytics,Hugo]
description=
Hugoにgoogle analytics(ga)を導入しようと思ったら意外と簡単だった。

まず、gaアカウントを作成。

config.tomlに

```
googleAnalytics = "{ga tracking ID}"
```

を設定するだけ。
