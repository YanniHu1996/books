# 投资书籍收藏

价值投资经典读物收藏，共 18 册。

## 书单

| 书名 | 作者 |
|------|------|
| 投资中不简单的事 | 邱国鹭 |
| 沃伦·巴菲特：终极金钱心智 | 罗伯特·哈格斯特朗 |
| 巴菲特幕后智囊：查理·芒格传 | 珍妮特·洛尔 |
| 投资的本质：段永平讲述投资的底层逻辑 | 孙力科 |
| 文明、现代化、价值投资与中国 | 李录 |
| 查理·芒格致股东的信 | 李永宁 |
| 段永平投资问答录：大道至简的财富逻辑 | 马小奔 |
| 一本书读懂财报 | 肖星 |
| 大道：段永平投资问答录 | 段永平 |
| 投资中最简单的事 | 邱国鹭 |
| 周期 | 霍华德·马克斯 |
| 巴菲特致股东的信：投资原则篇 | 杰里米·米勒 |
| 价值投资者的财报分析 | 夏立军、李莫愁 |
| 一个投机者的告白·实战版 | 安纳金 |
| 慢慢变富2：普通人的成功投资 | 闲来一坐s话投资 |
| 价值投资3.0 | 亚当·西塞尔 |
| 雪球名家带你价值投资（套装共6册） | 张延昆 等 |

## 在线访问

https://yannihu1996.github.io/books/

点击书籍条目即可下载 PDF 文件。

## 下载方式

**方式一：网页下载**
访问在线页面，点击书籍即可下载。

**方式二：克隆仓库**
```bash
git clone https://github.com/YanniHu1996/books.git
cd books

# 安装 Git LFS（如果尚未安装）
brew install git-lfs
git lfs install

# 拉取 LFS 文件（自动下载所有 PDF）
git lfs pull
```

## 本地预览

```bash
# 克隆仓库
git clone https://github.com/YanniHu1996/books.git
cd books

# 安装 Git LFS（如果尚未安装）
brew install git-lfs
git lfs install

# 拉取 LFS 文件
git lfs pull

# 本地预览页面
# 方式一：Python
python3 -m http.server 8000
# 访问 http://localhost:8000

# 方式二：Node.js
npx serve .
# 访问 http://localhost:3000
```

## 技术说明

- PDF 文件使用 Git LFS 管理
- 下载页面为纯静态 HTML/CSS/JS
- 托管于 GitHub Pages