### 这是蓝松SDK最简单的演示.
#### 当前版本是4.2.5
- 包括:视频编辑SDK和 AE模板SDK; 
- 我们完整的演示demo apk, 你可以从这里下载:
- APK下载：https://www.pgyer.com/L20O
- 如果你想测试我们的SDK, 可以向我们索取全部的演示源代码. 
 
 ## SDK功能介绍.
 #### 视频编辑SDK:
  - 类的名字是：LSOConcatComposition：意思是：拼接合成，可把视频和图片前后拼接在一起，也可上下叠加在一起；分别对应ConcatLayer和 overlayLayer；
  - 
  - **前后拼接**, 每拼接一个, 会返回一个图层对象;可用图层对象调节各种属性; 可插入, 可删除,可排序, 替换;
  - **上下叠加**：在拼接图片和视频的同时，可以在拼接的上面叠加图片或视频，文字，动画等效果，这些称之为上下叠加；比如画中画，可设置叠加的开始位置，大小，角度，开始时间点，结束时间点，是否循环，支持图层的所有特性，可调节上下层的次序；
  - **缩略图**	每个视频或图片增加后，会得到对应的缩略图，当裁剪或倒序或变速后，缩略图API会对应调整.
  - **手势操作**：在增加素材后，返回一个图层，是一层一层的图层设计，所有图层均支持手势；可单手指选中，移动；可双手指缩放和旋转； 
  - **动画**：有入场动画， 出场动画， 任意时间点动画；动画是用AE软件做好后， 导出为SDK支持的json格式，从而你可以自由发挥制作不同的动画，SDK端只需要一个导出文件，加载即可呈现动画效果。可预览，可删除，可应用到全部；
  - **转场**： 用AE设计好导出的json格式， 可做蒙版转场或移动旋转缩放透明转场，可删除，可预览，可应用到全部；
  - **特效**：也是用AE软件设计好， 然后导出json或我们指定的MP4文件；特效时间可调节，可预览，可调节，可删除，可应用到全部；
  - **蒙版**	在PC端用Photoshop制作， 导出为一张透明图片，增加到SDK中。可不同效果， SDK自动调节图片大小，并根据图片的透明度调节视频不同区域的透明度；
  - **编辑功能**：时长裁剪，画面裁剪， 旋转，镜像， 画面缩放， 不透明度；
  - **滤镜**：提供18种常见滤镜；并支持自定义；
  - **调节**：有亮度、对比度、饱和度、高亮、阴影；色调，白平衡；
  - **倒放**：倒叙播放；倒放和变速可同时设置；
  - **变速**：支持0.1--10倍的声音增加；
  - **声音图层**； 增加音乐， 录音，mp3声音， 从视频中提取的声音；
  - **音量**， 可0---8.0倍音量调节；0.0是无声；8.0是几乎破音的，建议2.0或3.0；
  - **图片图层**， 可做静态贴纸，动态贴纸，Gif贴纸；
  - **画中画**：可在拼接层上面叠加各种其他视频， 称之为合成图层；
  - **导出** 可导出不同分辨率

####  AE模板SDK
- 在PC端用Adobe After Effect设计了整个动画场景，在手机端让用户替换对应的图片, 设计时,图片可旋转移动缩放透明,高斯模糊, 3D效果;
- SDK端, 支持在播放的过程中,直接把图片替换为图片或视频
- 如果替换的位置有偏差, 则可以在播放过程中用手指单指移动, 双指缩放或旋转.
- 支持替换声音,增加logo, 对画面做滤镜, 增加其他文本等. 
- 支持导出的时候,设置不同的分辨率.
#### 联系我们
#### contact us
- email: support@lansongtech.com
- web: www.lansongtech.com
