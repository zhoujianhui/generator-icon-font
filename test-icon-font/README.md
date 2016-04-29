# test-icon-font
用于将svg格式的icons转换为iconfont字体格式

## Usage
1、将所需生成字体的svg放置在src/svg下

2、全局安装gulp-cli并启动gulp构建任务
```
npm install -g gulp-cli
gulp
```

3、使用iconfont
可参考生成的字体展示界面test-icon-font.html，它包含了所有字体图标的名称和展示

在你的html中引入字体样式
```
<link rel="stylesheet" href="test-icon-font.css">
```
使用字体图标
```html
<div class="icon-test">icon-test</div>
```
