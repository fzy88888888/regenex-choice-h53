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

## 推荐发布方式：腾讯云 EdgeOne Pages

这是当前更适合国内手机访问的方案。建议先把本文件夹里的内容上传到 GitHub 仓库根目录，再用 EdgeOne Pages 导入 GitHub 仓库。

### 1. GitHub 仓库文件要求

仓库根目录必须长这样：

```text
index.html
assets/
DEPLOY.md
```

不要出现这种结构：

```text
regenex-choice-h5/
  index.html
  assets/
```

否则部署后根路径容易 404。

### 2. EdgeOne Pages 创建项目

1. 打开 EdgeOne Pages 官网。
2. 登录腾讯云账号。
3. 进入 Pages 控制台。
4. 选择新建项目。
5. 选择从 Git 导入项目。
6. 授权 GitHub。
7. 选择仓库 `regenex-choice-h52`。

### 3. 构建配置

这是纯静态 HTML 项目，不需要构建命令。

```text
Framework preset: None / Other / Static
Build command: 留空
Output directory: /
Root directory: /
Install command: 留空
```

如果后台必须填写 Output directory，就填：

```text
.
```

### 4. 发布后检查

部署成功后，EdgeOne 会生成一个公开访问链接。打开链接后必须直接看到 H5 首页，而不是 GitHub 文件列表，也不是 404 页面。

建议用手机流量和微信内置浏览器分别测试一次。

## 注意

- 请不要只上传 `index.html`，必须连同 `assets/` 文件夹一起上传。
- `assets/poster-data.js` 用于解决手机端/本地环境下海报保存失败的问题，也必须保留。
- 当前二维码素材为产品/官网跳转二维码，不是 H5 页面二维码。拿到公网链接后，可以再单独生成作品访问二维码。
- 如果需要一年以上稳定链接，建议给 EdgeOne Pages 绑定一个购买 1 年以上的自定义域名。

## 参赛提交可用信息

- H5 公网链接
- 作品二维码
- 作品名称：《选择权补给站》
- 类别：Da 线上互动广告
- 主题：朗圣药业“随心所育，绽放人生之美”
