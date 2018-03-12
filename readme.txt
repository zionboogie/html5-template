* �ŏ����̃e���v���[�g
min_template.html

* header�Anav�Ȃǂ����炩���ߗp��
min_layout_template.html

* min_layout_template.html���x�[�X��Sass�Ή�
min_layout_sass_template.html

* ie9�ȉ��ɂ��Ή�����
lt_ie9.html




## HTML5�ŏ���
``` html
<!DOCTYPE html>
```

## CSS�n�b�N��IE�Ή�
``` html
<!--[if lt IE 7 ]><html class="ie ie6" lang="ja"><![endif]-->
<!--[if IE 7 ]><html class="ie ie7" lang="ja"><![endif]-->
<!--[if IE 8 ]><html class="ie ie8" lang="ja"><![endif]-->
<!--[if (gte IE 9)|!(IE)]><!--><html lang="ja"><!--<![endif]-->
```

## ���[�U�[�G�[�W�F���g�̐ݒ�
IE�̍ŐV�o�[�W�����̕W�����[�h�ŕ\�����܂��B
``` html
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

## viewport
�������f�o�C�X���ɍ��킹��
``` html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

## OGP
``` html
<meta property="og:title" content="�^�C�g��">
<meta property="og:type" content="website">
<meta property="og:url" content="http://�C�ӂ�URL">
<meta property="og:image" content="http://�C�ӂ�URL/og_image.png">
<meta property="og:site_name" content="">
<meta property="og:description" content="" />
<meta property="fb:app_id" content="�C�ӂ�ID">
```

## CSS
``` html
<link rel="stylesheet" href="css/style.css">
```


## jQuery�iCDN�j
``` html
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<script> (window.jQuery || document .write('<script src="js/jquery-1.11.2.min.js"><\/script>')); </script>
```

## IE8�ȉ����Ή��������ꍇ
``` html
<!--[if lt IE 9]>
	<script src="js/html5.js"></script>
	<script src="js/IE9.js"></script>
	<script src="js/css3-mediaqueries.js"></script>
<![endif]-->
```

## header
�y�[�W�w�b�_�[
``` html
<header class="pg-header" role="banner">
</header>
```

## nav
�O���[�o���i�r�Q�[�V����
``` html
<nav class="g-navi" role="navigation">
</nav>
```

## main
���C���R���e���c
``` html
<main role="main">
</main>
```

## aside
�T�C�h�R���e���c
``` html
<aside role="complementary">
</aside>
```
## footer
�y�[�W�t�b�^�[
``` html
<footer class="pg-footer" role="contentinfo">
</footer>
```


## css/style.scss
normalize.css�Anormalize.css���J�X�^�}�C�Y����ress.css�AHTML5 Doctor�̃��Z�b�gCSS�̗�����p�ӂ��Ă��܂��B
�v�f�̓������c���A�u���E�U�Ԃ̍��ق��Ȃ��Ȃ�悤�ɂ������ꍇ��normalize.css��ress.css�A���X�g�̍��ۂȂǂ̃X�^�C�������Z�b�g�������ꍇ��HTML5 Doctor��reset.css���g���Ă��������B
