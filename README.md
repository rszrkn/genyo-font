![banner](genyo-cover-tw.png?raw=true)

# 源樣明體

「源樣明體」是基於[思源宋體](https://github.com/adobe-fonts/source-han-serif/)的開放原始碼中文字型。
採用思源宋體韓文（KR）版本的字符，配合繁體中文慣用的置中標點，可排版傳統印刷體風格的文件。

## 特徵

### 傳統印刷體

思源宋體預設的台灣版本（TW）採用教育部標準字體，雖然適合教育用途，但不盡符合傳統印刷體審美觀。
例如點、挑、撇筆畫太多，文件排列時的的跳動感較大。
此專案採用KR版本的字符為主，較接近傳統印刷體習慣，排列感較為整齊。

> Note: 本專案並沒有造新的字符，所有字符都是來自思源宋體本身。所以KR版本未收錄的罕用字或簡化字，仍然會是TW、CN風格。

### 漢字不缺字

保留思源宋體所支援之所有漢字（包或日、韓文漢字與簡體字），一般會用到的漢字幾乎不會有缺字問題。
同時也保留了所有日文假名。（但刪除了高達1萬字的韓文字，有效降低字型檔大小。）

> Note: 本專案並沒有造新的字符，簡體字等當然會是CN風格。

### 標點符合繁體中文習慣

直接使用思源宋體KR版本排中文，會有標點置於左下的問題。
此版本的標點符號仍採用繁體中文習慣，逗號、句號等都置於正中央。
並且系統能正確識別為繁體中文字型。

另外，思源宋體的標點符號如「，」「。」設定有比例寬度的壓縮字寬，在Illustrator、InDesign等環境下預設會壓縮50%顯示。這往往會讓標點顯得過窄。
此版本移除了部分符號的壓縮字寬資訊，讓這些標點符號字寬原則上保持全形。

### TrueType格式

字型已經轉換成TrueType格式（.ttf）。
在Word、PowerPoint等軟體支援都較為完整（例如可以正常內嵌在投影片裡）。
對一些老舊的應用程式相容性都較高。

### 解決一些其他思源宋體使用上的雜問題

* 解決在Illustrator中，文字行高過高，不容易選到正確行的問題。
* 解決在Word中，標準文字大小12pt時文字佔兩倍行高的問題。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」。

## 此為公測版

目前仍是Beta公測版本，未來本專案不排除有大幅更改規格的可能性。
歡迎提供測試反饋，請直接反饋在GitHub的Issues中。
未來亦不保證持續跟隨思源宋體升版。
