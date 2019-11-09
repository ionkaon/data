# 寧波方言資料整理

- [《阿拉宁波话(修订版)》索引](https://github.com/shinzoqchiuq/gninpou-dialect#阿拉宁波话修订版索引)
- [The Ningpo Syllabary](https://github.com/shinzoqchiuq/gninpou-dialect#The-Ningpo-Syllabary)
- [《寧波方言詞典》詞條](https://github.com/shinzoqchiuq/gninpou-dialect#寧波方言詞典詞條)

## 《阿拉宁波话(修订版)》索引

初版《阿拉宁波话》出版於 1991 年，於 2016 年出版了修訂版。修訂版 ISBN：9787552626599。

書中「修订版后记」一節提到：

> 本书与初版一样，有一个缺陷，就是没有索引，因为本书不是词典性质的，内容丰富多彩，制作索引既很困难，又占篇幅。没有索引，不便检索书中的方言词、短语、谚语等，会给读者带来不便，对此，我们表示歉意。

文件 [`《阿拉宁波话(修订版)》索引.tsv`](《阿拉宁波话(修订版)》索引.tsv) 爲《阿拉宁波话(修订版)》中的方言詞和短語製作了索引。

文件共分爲五列，列與列之間使用 tab 鍵隔開。第一列爲繁體的詞頭，第二列爲簡體的詞頭，第三列爲吳語拼音，第四列是分類，第五列是該詞條所在的頁碼。使用者可以用文本編輯器的搜索功能來查詢詞條，再通過相應的頁碼找到詞條在原書中的位置。

索引還將書中提到的又音某、又作某、也作某等單獨列爲了詞頭。

書中有些生僻字未被收錄到Unicode中，一般用 [IDC](https://en.wikipedia.org/wiki/Ideographic_Description_Characters_(Unicode_block))（表意文字描述字符）表示，但也有例外。如「⿰日仓」字未被收錄到 Unicode 中，索引裏使用了「𪰻」字來替代。

又有部分生僻字如「𧟰」字，爲了方便讀者查找，使用了更常見的「覅」來替代。又如「𫧃」（「⿰勿会」）字位於 Unicode 擴展 E 區，多數設備無法支持，索引中使用了「𠊉」字替代。

## The Ningpo Syllabary

《The Ningpo Syllabary》出版於 1901 年，作者是德國語言學家 [穆麟德](https://en.wikipedia.org/wiki/Paul_Georg_von_Möllendorff) （P. G. von Möllendorff）。其中同音字表部分爲夏清瑞在穆麟德的指導下完成。書中採用了 [丁韙良](https://en.wikipedia.org/wiki/William_Alexander_Parsons_Martin) 等人在 1951 年創制的一套寧波話拼音，並在引言中對這套拼音做了詳細的描述。

文件 [`The_Ningpo_Syllabary.txt`](The_Ningpo_Syllabary.txt) 中抄錄了原書第 1 頁～第 54 頁的同音字表。

書中拼音首字母均用大寫，抄錄時全部改爲小寫。

書中有部分漢字未被收錄到 Unicode 中，抄錄時使用 [IDC](https://en.wikipedia.org/wiki/Ideographic_Description_Characters_(Unicode_block)) 來表示。

書中有部分音節收字有重複，在抄錄過程中刪去了這些重複收錄的字。

書中同音字表內的部分拼音拼寫與引言中不同。對比使用同一拼音方案的《寧波方言字語彙解》（睦禮遜惠理，1876），可以確認引言中的拼寫是正確的。在抄錄時將同音字表的拼寫做了修正，包括如下幾條：

- 引言作 üing，同音字表作 iüng
- 引言作 üih，同音字表作 iüh
- 引言作 l̆，同音字表作 lʽ
- 引言作 n̆，同音字表作 nʽ
- 引言作 n̆g，同音字表作 nʽg

在抄錄時還修正了同音字表中的一些印刷錯誤。包括：

- sôh 誤作 sôp
- tsʽ 誤作 tʽs
- un 誤作 uu
- ün 誤作 üu

需要注意的是，拼音方案裏表示濁音或送氣的符號並非引號，而是 [粗氣符](https://en.wikipedia.org/wiki/Rough_breathing)「ʽ」。在抄錄時未對其做改動。

## 《寧波方言詞典》詞條

文件 [`《寧波方言詞典》詞條.tsv`](《寧波方言詞典》詞條.tsv) 整理了江蘇教育版《寧波方言詞典》中的詞條。

文件共分爲四列，第一列是整理爲 [OpenCC](https://opencc.byvoid.com/) 標準的詞頭，第二列是原書書中的詞頭，第三列爲簡體，第四列是詞語對應的吳語拼音。多字詞的聲調尚未整理，故現在只有單字詞有標註聲調。

書中未被 Unicode 收錄的生僻字，使用 [IDC](https://en.wikipedia.org/wiki/Ideographic_Description_Characters_(Unicode_block)) 表示。

書中在字下面加小圓圈來表示同音替代，文件內使用在字後面加「○」的方式表示。

## 《鄞縣通志》詞彙索引（未完成）

《鄞縣通志》原書詞彙讀音使用注音符號標註，原書爲適應寧波音系，制定了幾個擴展注音符號。這些符號未被 Unicode 收錄，故 [`《鄞縣通志》詞彙索引.txt`](《鄞縣通志》詞彙索引.txt) 中的使用吳語拼音來標註讀音。音系與拼音方案如下：

![《鄞縣通志》音系](https://raw.githubusercontent.com/shinzoqchiuq/gninpou-dialect/thon-tsy/《鄞縣通志》音系.png)

## 反饋

限於本人水平，整理的資料中難免會有錯漏。如果使用者有任何問題或是發現了任何錯誤，歡迎提交 [issue](https://github.com/shinzoqchiuq/gninpou-dialect/issues)，或是通過以下郵箱直接與我聯繫。

本人郵箱：1613023143@qq.com
