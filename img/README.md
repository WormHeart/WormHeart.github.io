# 个人静态资源目录

把你的图片放到这里，**`source/img/` 下的同名文件会自动覆盖主题 `themes/fluid/source/img/`** 中的默认图。

## 推荐替换的文件

| 文件名 | 用途 | 推荐尺寸 |
| --- | --- | --- |
| `avatar.png` | 关于页头像 | 256×256 或 512×512 正方形 |
| `default.png` | 首页 / 文章页 / 归档页 / 关于页的顶部 Banner | 1920×1080 或更宽，横幅风景照效果最好 |
| `fluid.png` | 浏览器标签 favicon | 32×32 或 64×64 |
| `loading.gif` | 图片懒加载占位 GIF | 任意 |
| `random/*.png` | 头图随机轮播池（需在 `_config.fluid.yml` 把 `banner.random_img: true`） | 与 `default.png` 一致 |

## 如何换图

1. 把你的图片重命名为对应名称（如 `avatar.png`）
2. 直接复制到这个目录里
3. `hexo clean && hexo g && hexo s` 即可看到效果

> 当前没有放任何自定义图片，站点会自动 fallback 到 `themes/fluid/source/img/` 下 Fluid 主题自带的占位图。
