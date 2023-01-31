# Easychat

用于DOLLARS聊天室的**简易**脚本，方便小白使用。

## 效果图

![移动端](http://i.miaosu.bid/data/f_31711428.jpg)
![PC端](https://s3.bmp.ovh/imgs/2022/07/23/48a6442f429a54d1.jpg)


## 使用方法
- 电脑端

“F12”键 → console 输入以下代码：
```
var script = document.createElement('script');
script.src = "https://mess20.github.io/DOLLARS-Extension/content.js";
$('head')[0].appendChild(script);
```

- 手机端

部分浏览器可以使用。

“脚本”中添加，

或选择“开发者工具” → console 输入上述代码：

## 唤起
按右下角绿色按钮即可。

## 功能
#### 功能开关
文字后面是开关按钮，很粗暴地点一次就是开启状态，再点一次就是关（或者恢复默认设置）。

#### 上传图片
提供几个图床网站的链接，点击网站名即跳转。


#### 自动续房
采用每10分钟报时一次的方法实现。

- 手机端只有留在浏览器才能确保该功能正常运行。

#### 自动小字
按post键发言自动小字；键盘直接发送不变。

#### 进房提示
有人进房会弹出“Someone entered room.”消息框。

#### 更换背景
更换聊天背景为指定图片。提供输入图片URL和上传本地图片两种方式。

注意：
- 图片大小尽量与屏幕大小一致。
- URL格式有误不会报错。

#### 更改字体
更改聊天界面字体（font-family）。

- 可同时填多种字体类型，例：`Tahoma,Arial,sans-serif`

已知手机端可显示字体：
- sans-serif（网站所设聊天字体类型）
- times
- monospace

#### 字体大小
更改聊天字体大小（font-size）。

网站所设聊天字体大小为 16px。

#### 字体颜色
更改聊天字体颜色。

可填颜色模式：
- 自然语言 例：`black`
- HEX 例：`#000000`
- RGB、RGBA 例：`rgb(0,0,0)`，`rgba（0,0,0,1）`
- HSL、HSLA 例：`hsl(0,100%,50%)`，`hsla(0,100%,50%,1)`


## 插件 [DOLLARS Extension](https://github.com/mess20/DOLLARS-Extension)
功能与脚本完全相同。
### 安装方法
下载：

① （电脑端）前往[页面](https://github.com/mess20/DOLLARS-Extension) > 点击 code > 点击 download zip 下载压缩文件

② 直接点击[链接](https://codeload.github.com/mess20/DOLLARS-Extension/zip/refs/heads/main)下载压缩文件

安装：进入拓展程序 > 开启开发者模式 > 点击 load > 选择已下载至本地的拓展文件

### 使用说明

- 手机端不支持后台运行、锁屏时运行。

- 如果有不清楚的，附上 [说明](https://mess20.github.io/TiddlyWiki/Tempor/code#%E3%80%90%E9%99%84%E5%BD%95%E8%AF%B4%E6%98%8E%E3%80%91%EF%BC%88android%E7%B3%BB%E7%BB%9F%EF%BC%89:%E3%80%90%E9%99%84%E5%BD%95%E8%AF%B4%E6%98%8E%E3%80%91%EF%BC%88android%E7%B3%BB%E7%BB%9F%EF%BC%89%20Tempor%20%E6%83%A8%E7%97%9B%E7%9A%84%E6%95%99%E8%AE%AD%20%E5%BF%AB%E6%8D%B7%E9%94%AE)


### 更新日志

2023/1/27 解决程序夺输入框的问题
2023/1/31 优化CSS，新增延时发送功能













