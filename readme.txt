* 最小限のテンプレート
min_template.html

* header、navなどをあらかじめ用意
min_layout_template.html

* min_layout_template.htmlをベースにSass対応
min_layout_sass_template.html

* ie9以下にも対応する
lt_ie9.html




## HTML5で書く
``` html
<!DOCTYPE html>
```

## CSSハックでIE対応
``` html
<!--[if lt IE 7 ]><html class="ie ie6" lang="ja"><![endif]-->
<!--[if IE 7 ]><html class="ie ie7" lang="ja"><![endif]-->
<!--[if IE 8 ]><html class="ie ie8" lang="ja"><![endif]-->
<!--[if (gte IE 9)|!(IE)]><!--><html lang="ja"><!--<![endif]-->
```

## ユーザーエージェントの設定
IEの最新バージョンの標準モードで表示します。
``` html
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

## viewport
横幅をデバイス幅に合わせる
``` html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

## OGP
``` html
<meta property="og:title" content="タイトル">
<meta property="og:type" content="website">
<meta property="og:url" content="http://任意のURL">
<meta property="og:image" content="http://任意のURL/og_image.png">
<meta property="og:site_name" content="">
<meta property="og:description" content="" />
<meta property="fb:app_id" content="任意のID">
```

## CSS
``` html
<link rel="stylesheet" href="css/style.css">
```


## jQuery（CDN）
``` html
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<script> (window.jQuery || document .write('<script src="js/jquery-1.11.2.min.js"><\/script>')); </script>
```

## IE8以下も対応したい場合
``` html
<!--[if lt IE 9]>
	<script src="js/html5.js"></script>
	<script src="js/IE9.js"></script>
	<script src="js/css3-mediaqueries.js"></script>
<![endif]-->
```

## header
ページヘッダー
``` html
<header class="pg-header" role="banner">
</header>
```

## nav
グローバルナビゲーション
``` html
<nav class="g-navi" role="navigation">
</nav>
```

## main
メインコンテンツ
``` html
<main role="main">
</main>
```

## aside
サイドコンテンツ
``` html
<aside role="complementary">
</aside>
```
## footer
ページフッター
``` html
<footer class="pg-footer" role="contentinfo">
</footer>
```


## css/style.scss
normalize.css、normalize.cssをカスタマイズしたress.css、HTML5 DoctorのリセットCSSの両方を用意しています。
要素の特徴を残しつつ、ブラウザ間の差異がなくなるようにしたい場合はnormalize.cssかress.css、リストの黒丸などのスタイルもリセットしたい場合はHTML5 Doctorのreset.cssを使ってください。
