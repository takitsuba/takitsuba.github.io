Jupyter Labで実行中、Kernel Restartingが出ることがある。

もしdockerで起動してるなら、
```
docker stats
```

でメモリの使用率をみると良いかも。
メモリオーバーで Kernel Restartingが起きてることがある。
