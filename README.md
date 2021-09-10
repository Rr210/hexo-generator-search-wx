# hexo-generator-search-wx

> 基于hexo-generator-search, 改动增加文章文件别名, 方便配置小程序接口, 详细配置看[hexo-generator-search](https://www.npmjs.com/package/hexo-generator-search)

## 小程序项目

* [x] [点击跳转到hexo小程序项目](https://github.com/Rr210/hexo-wx-api)

## Install

```bash
$ npm install hexo-generator-search-wx --save
```

## Options

You can configure this plugin in your root `_config.yml` .

```yaml
search:
  path: search.xml
  field: post
  content: true
```

* **path** - file path. By default is `search.xml` . If the file extension is `.json`, the output format will be JSON. Otherwise XML format file will be exported.
* **field** - the search scope you want to search, you can chose:
  + **post** (Default) - will only covers all the posts of your blog.
  + **page** - will only covers all the pages of your blog.
  + **all** - will covers all the posts and pages of your blog.
* **content** - whether contains the whole content of each article. If `false`, the generated results only cover title and other meta info without mainbody. By default is `true`.
