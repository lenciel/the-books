# the-books

一个放我自己读书笔记或者翻译的书的静态站点。使用 Jekyll 但是做了一些定制：

- 支持自动 `father-menu-name` 生成二级菜单（书很多有大小章节）。
- 支持根据文件名的顺序自动生成翻页（section nav）[^1]。
- 
## 安装运行

当成一个正常的 Jekyll 网站就行。

```bash
bundle install
jekyll s -i -w
```

## Usage

### 添加一本书

需要下面几个步骤：

1. 在 `_config.yml` 里面声明一个 `collection`，注意 Jekyll 的默认设置一个 collection 的文件是放在它的 label 前面加下划线的目录里面。
2. 在 `_data/docs_nav.yml` 里添加相应声明
3. 在 `books` 文件夹里面创建一个书的入口页

然后在 collection 目录里面添加文件就好。


## Contributing

Let’s see what will happen.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

