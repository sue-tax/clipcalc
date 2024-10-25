# clipcalc　主な機能

## 式をクリップボード経由で計算
　クリップボードにコピーした式を計算して
計算結果をクリップボードにコピーします。

　メールソフト等に入力した計算式を
Ctrl+cでコピーした後、（ウィンドゥを切替えずに）
Alt+xまたはAlt+?を押すと計算するので、
計算結果をCtrl+vでペーストできます。

## 様々な式の表現
　カンマ入りの数字、全角数字、億・万などでも、
計算できます。
　計算に関係ない文字は無視します。

「売却益五千万×所得税率１５％*1.021」
を式として計算できます。

## 分数などの正確な計算
　「(100/30)*9」を29.9999…ではなく、30と計算します。

## 単位による計算
　ｍ・ｃｍや分・秒などの単位付きの計算ができます。
　「１ｍ＋５０ｃｍ」は、１．５ｍになります。

## 消費税・源泉税計算
　消費税の計算や源泉税の計算もできます。

# バージョン
## 0.4.2b
(-3)^2　や　4^(-2) のような計算は、仕様外として、行いません。

## 0.4.3
(-3)^2　や　4^(-2) のような計算に対応しています。

(-3)^1.5 のような計算はできませんが、エラーとならずに、永遠に計算を続けますので、注意してください。

強制的にプログラムを終了しても、終了せずに計算を続けている場合があります。タスクマネージャーで終了させるのが確実です。

## 0.4.3b（未公開）

(-2)^1.5をエラーとしました。

## 0.4.4（未公開）

a,b 1 などをエラー表示する

## 0.4.4a

0.4.4と同じ。（開発環境の変更のみ）

McAfee などで、セキュリティチェックにより削除されることがあります。

## 0.4.5

２００円など数字以外がある場合でも、消費税計算・源泉税等計算をできるようにしました。

## 0.5.0

TeXの数式のうち分数`\frac{分子}{分母}`、累乗根`\sqrt[3]{27}`,`\pi`による計算をできるようにしました。
