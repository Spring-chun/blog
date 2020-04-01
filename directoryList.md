### 项目目录
```javascript
|-- blog_code
    |-- .DS_Store
    |-- .gitignore
    |-- 404.html
    |-- Gemfile
    |-- LICENSE.txt
    |-- README.md
    |-- _config.yml //保存配置数据。很多配置选项都会直接从命令行中进行设置，但是如果你把那些配置写在这儿，你就不用非要去记住那些命令了。
    |-- index.md
    |-- plainwhite.gemspec
    |-- screenshot.png
    |-- sitemap.xml
    |-- _includes
    |   |-- head.html
    |-- _layouts
    |   |-- default.html
    |   |-- home.html
    |   |-- page.html
    |   |-- post.html
    |-- _posts //这里放的就是你的文章了。文件格式很重要，必须要符合: YEAR-MONTH-DAY-title.MARKUP。 The permalinks 可以在文章中自己定制，但是数据和标记语言都是根据文件名来确定的
    |   |-- .DS_Store
    |   |-- 2019-03-23-welcome-to-jekyll.markdown
    |-- _sass
    |   |-- _syntax.scss
    |   |-- plain.scss
    |   |-- ext
    |       |-- _fonts.scss
    |       |-- _normalize.scss
    |       |-- _solarized-light.scss
    |-- assets
        |-- .DS_Store
        |-- portfolio.png
        |-- css
        |   |-- style.scss
        |-- font
            |-- fontello.eot
            |-- fontello.svg
            |-- fontello.ttf
            |-- fontello.woff
            |-- fontello.woff2
```