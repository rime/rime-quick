# 速成輸入法

配方： ℞ **quick**

[Rime](https://rime.im) 速成輸入方案

速成取倉頡碼的首尾二碼

本方案支持詞句連書、自動調整詞頻、記憶新詞

單碼字可綴以 `;` 或 `'` 鍵與後字的編碼隔開

以 <code>`</code> 鍵開始輸入拼音反查速成碼

## 安裝

[東風破](https://github.com/rime/plum) 安裝口令： `bash rime-install quick cangjie`

構建時依賴（Build dependency）：

  - [倉頡](https://github.com/rime/rime-cangjie) ℞ **`cangjie`**

編譯速成輸入法詞典時，要用到倉頡配方包中的 `cangjie5.base.dict.yaml` 碼表文件；

製成 `quick5.*.bin` 後，使用速成輸入法打字不再需要倉頡方案、詞典。

授權條款：見 [LICENSE](LICENSE)
