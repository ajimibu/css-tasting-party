# CSS Flexible Box Layout Module
http://www.w3.org/TR/2012/WD-css3-flexbox-20120612/

## 超概要
display: flex または display:inline-flex をつけると flex container になる。
flex container に入れた子要素が flex items として、Flex layout モデルをつかって
レイアウトされる。

	body>div {
		display: -webkit-flex;
		display: flex;
	}

## 子要素を列方向に配置する

	flex-flow: row 				/* 左から右へ（デフォルト） */
	flex-flow: row-reverse		/* 右から左へ */

## 子要素を行方向に配置する

	flex-flow: column 			/* 上から下へ */
	flex-flow: column-reverse	/* 下から上へ */

## 折り返しの制御

	flex-flow: nowrap;			/* 折り返ししない（デフォルト） */
	flex-flow: wrap;			/* 順方向に折り返す */
	flex-flow: wrap-reverse;	/* 逆方向に折り返す */

## その他
これは FlexBox のごく一部の仕様で、他については未調査です：

	order:
	single-line:
	multi-line:
	flex:
	flex-grow:
	flex-shrink:
	flex-basis
