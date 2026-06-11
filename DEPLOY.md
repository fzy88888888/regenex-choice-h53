# 朗圣药业《选择权补给站》H5 静态托管说明

## 文件结构

这是纯静态 H5，托管时上传整个 `regenex-choice-h5` 文件夹即可，入口文件是：

```text
index.html
```

资源目录是：

```text
assets/
```

## 最快发布方式：Netlify Drop

1. 打开 https://app.netlify.com/drop
2. 登录 Netlify。
3. 将整个 `regenex-choice-h5` 文件夹拖到页面中。
4. 等待上传完成，Netlify 会生成一个公开访问链接。
5. 用手机打开这个公开链接即可体验 H5。

## 备选方式：Cloudflare Pages

1. 打开 https://dash.cloudflare.com/
2. 进入 Workers & Pages。
3. 选择 Pages -> Upload assets。
4. 上传整个 `regenex-choice-h5` 文件夹。
5. 发布后获得公开链接。

## 备选方式：Vercel

1. 打开 https://vercel.com/
2. 新建 Project。
3. 上传或导入包含 `regenex-choice-h5` 的仓库。
4. Framework Preset 选择 Other。
5. Output Directory 留空或选择当前目录。
6. 发布后获得公开链接。

## 注意

- 请不要只上传 `index.html`，必须连同 `assets/` 文件夹一起上传。
- `assets/poster-data.js` 用于解决手机端/本地环境下海报保存失败的问题，也必须保留。
- 当前二维码素材为产品/官网跳转二维码，不是 H5 页面二维码。拿到公网链接后，可以再单独生成作品访问二维码。

## 参赛提交可用信息

- H5 公网链接
- 作品二维码
- 作品名称：《选择权补给站》
- 类别：Da 线上互动广告
- 主题：朗圣药业“随心所育，绽放人生之美”
