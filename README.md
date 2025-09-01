###　如果您需要移除ipynb文件，可以参照：
#### windows：
```
Get-ChildItem -Path . -Recurse -Filter *.ipynb | Remove-Item
```

#### linux
``bash
find . -type f -name "*.ipynb" -delete
```
