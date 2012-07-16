网页嵌入藏文字体示例v4 特别定制版（动态嵌入藏文字体方案）2012-07-16  zip压缩版

嵌入字体 
font Detect  
auto download webfont  
网页嵌入字体  
网页嵌入
字体判断
嵌入藏文
动态嵌入


说明：
完美显示藏文：
没有藏文字体的电脑,下载藏文的webfont来显示
含有藏文字体的电脑，使用电脑上的字体来显示

笔者想到的应用范围：
在没有安装藏文字体的电脑显示：
1.藏文chm文件
2.藏文网站
3.离线的藏文书籍，比如《甘珠尔》

更新说明
2012-7-16：
1. fontdetect.js作者有更新到0.3，更新了这个js文件
2. 动态加载藏文字体时，开始时文字全部显示为框框，优化使其流畅显示

2012-03-23：
1. 本次特别定制版基于不丹宗卡藏文字体的DDC_Uchen，该字体基于OFL 授權（SIL Open Font License）http://scripts.sil.org/OFL
2.更多详情请查看 http://code.google.com/p/myyuanma/wiki/TibetanWebFont 
3.特别说明：喜马拉雅和珠穆朗玛系列字体因为字体授权不明，所以没有采用。
4.如有更新，最新版下载地址为：
http://code.google.com/p/myyuanma/downloads/list?can=2&q=AutoLoadWebfont&colspec=Filename+Summary+Uploaded+ReleaseDate+Size+DownloadCount
5.在线演示页面（首页）：http://myyuanma.googlecode.com/svn/trunk/autoDetect-AutoLoadWebfont-DDC_Uchen-V3/index.html

2012-03-22：
1. bug修复：修复只有firefox才正常显示的bug——原因：css中指定的webfont路径错误——忘记写相对路径。
2. fontdetect.js作者有更新，将fontdetect.js更新成新版Version: 0.2 (04 Mar 2012)
3. 删除对prototype的开源js库的依赖——仅仅一个函数，有替代方案，没必要用prototype