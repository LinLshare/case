## case

**替換字符串中的空格**

請編寫一個方法，將字符串中的空格全部替換為「%20」。 假定該字符串有足夠的空間存放新增的字符，並且知道字符串的真實長度(小於等於1000)，同時保證字符串由【大小寫的英文字母組成】。 給定一個string為原始的串，返回替換後的string。

## solution

### f1

構造一個新的字符數組，遍歷舊的字符數組並替換後插入新的字符數組。代碼見 [函數f1](main.go)。

### f2

判斷字符串的合法性後，使用 stirngs.Replace 替換字符串。代碼見 [函數f2](main.go)。