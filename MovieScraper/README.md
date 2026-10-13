# MovieScraper - 芝杜海报墙刮削器

自动扫描本地电影 / 剧集文件夹，匹配 TMDB 元数据，生成芝杜（Zidoo）海报墙所需的 `movie.nfo` / `tvshow.nfo`、单集 NFO、海报与剧集图片。支持手动匹配、跳过已刮削、现代 Web 风格暗色界面，便携免安装。

> **下载安装包**：前往 [Releases 页面](https://github.com/1205093639/XiaoBuTools/releases) 选择版本下载。

## 版本历史

| 版本 | 文件 | 更新说明 |
|---|---|---|
| v0.1.1 | [下载](https://github.com/1205093639/XiaoBuTools/releases/download/moviescraper-v0.1.1/MovieScraper-Portable-0.1.1.exe) | 修复分类文件夹识别：支持“电影”“剧集”等分类容器，正确扫描其内部影片/剧集 |
| v0.1.0 | [下载](https://github.com/1205093639/XiaoBuTools/releases/download/moviescraper-v0.1.0/MovieScraper-Portable-0.1.0.exe) | 首个版本：TMDB 电影/剧集刮削、手动匹配、芝杜 NFO 与海报生成；单文件免安装 |

## 使用步骤

1. 从 [Releases](https://github.com/1205093639/XiaoBuTools/releases) 下载最新版 exe，双击运行
2. 在设置中填入自己的 TMDB API Key（免费申请：https://www.themoviedb.org/settings/api）
3. 点击「选择文件夹」添加要刮削的媒体库目录
4. 点击「开始刮削」，等待程序自动识别并生成 NFO 与海报
5. 刮削完成后用芝杜播放器扫描该文件夹即可识别海报墙

## 功能说明

- 自动识别电影与剧集（支持常见命名格式）
- 手动搜索匹配，解决自动识别失败的情况
- 跳过已刮削文件，避免重复写入
- 过滤系统/隐藏文件夹（如 `$RECYCLE.BIN`）
- 生成芝杜海报墙标准 NFO 与封面图片
- 关于页附带作者 B 站主页与打赏支持（微信 / 支付宝）

## 常见问题

- **提示需要 TMDB API Key？** 首次使用请在设置中填入自己的 Key；TMDB 免费注册后即可申请
- **刮削结果不对？** 选中影片后点击「手动匹配」，输入正确中文/英文名重新搜索
- **源码与问题反馈**：[MovieScraper 源码仓库](https://github.com/1205093639/MovieScraper)
