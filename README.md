# Blog-images
> Images bed repository.

图床，用来放 `Xingshi.blog` 的图片的仓库。

图片压缩用的是 [squoosh-cli](https://github.com/GoogleChromeLabs/squoosh), 可惜 cli 项目现已停止维护了

不过在 `git bash` 中使用这个命令还是能压缩图片的，可以试试

```
squoosh-cli --webp '{"quality":75}' -d output_dir ./*.jpg
```

或者用他的网站代替，[squoosh.app](https://squoosh.app/)，这个还暂时没有停止维护关站呢