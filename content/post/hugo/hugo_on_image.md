title=Hugoの記事に画像を載せる
slug=hugo_on_image
tags=[Hugo]
Hugoに画像を載せるときは、[shortcodes](https://gohugo.io/content-management/shortcodes/)を使うと良いらしい。

画像の場合は、static/media以下に画像ファイルが置いてある状態で、次のように書く。

```
\{{</* figure src="/media/spf13.jpg" title="Steve Francia" width="320" height="640" */>}}
```

画像のサイズも指定可能。

ここでは、shortcodesをエスケープさせるために、/*を使っている。

```
{{</* code */>}}
```


すると、次のようなHTMLが出力される。

```
<figure>
  <img src="/media/spf13.jpg"  />
  <figcaption>
      <h4>Steve Francia</h4>
  </figcaption>
</figure>
```
