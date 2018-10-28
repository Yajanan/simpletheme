# simpletheme

[English](README.md)|中文

Hexo主题

一个简单到简陋的主题。


## 使用

### 安装

```bash
$ git clone https://github.com/Yajanan/simpletheme.git themes/simpletheme
```

### 使用 
将 `_config.yml` 中的`theme`选项改成 `simpletheme`。

### 更新

```bash
cd themes/simpletheme
git pull
```

## 代码高亮

```yaml
hljs:
  enable: true #true to enable the plugin
  line_number: frontend # add line_number in frontend or backend
  trim_indent: backend # trim the indent of code block to prettify output. backend or front-end (recommend)
  copy_code: true # show copy code in caption.
  label:
    left: Code
    right: ':'
    copy: Copy Code
```
将`_config.yml`中`highlight`下的 `enable` 选项改为false，然后将上面的内容添加进`_config.yml`。

## 特性

简单，简单 ，非常简单。

### 首页

![hexo-simpletheme-home](https://raw.githubusercontent.com/Yajanan/my-images/master/hexo-simpletheme-home.png)

### 文章页

![hexo-simpletheme-article](https://raw.githubusercontent.com/Yajanan/my-images/master/hexo-simpletheme-article.png)



## 链接

[HEXO](https://hexo.io/)

## 开源协议（License）

```html
MIT License

Copyright (c) 2018 Yajanan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```





