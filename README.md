


# TS declaration-file to documentation(xlsx)

由.d.ts檔抓出各lib/function的定義與註解，以供相關人員檢視。

## Usage

根目錄建立to-reads資料夾，將需要彙整的資料放入其中後，執行

```
node build/main.js
```

### Tips

1. All comments with *`/** */`* for Object with let declaration or functions/methods will be exported.
2. To export blank function def => /** */ 
