EvaPinyin
=========

A simple Chinese characters to pinyin lib. Original Author is Kin(Mr.kin@foxmail.com), modified by AlloVince for support PSR-2 and Composer.

All including 20850 Chinese characters. This lib **NOT ABLE** to handle polyphone. Only support UTF-8.

Usage:

``` php
$pinyin = new EvaPinyin\Pinyin();
echo $pinyin->transformWithTone('拼音');
//pīn yīn

echo $pinyin->transformWithoutTone('拼音', ' ');
//pin yin

echo $pinyin->transformUcwords('拼音');
//PY
```


