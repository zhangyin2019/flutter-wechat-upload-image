# flutter-wechat-upload-image
### 初衷
在实际APP开发中，像微博或者微信朋友圈的图片上传是必不可少的组件，经过封装，以此分享

### 使用方法
* pubspec.yaml中安装
```java
reorderable_grid: ^1.0.2
images_picker: ^1.2.7
```

* 使用的地方
注意：要达到微信图片预览的从小变大从图片位置直至满屏的效果，一定要加Hero
```dart
Expanded(
    child: UploadImage(
      padding: Common.edge_10_20_30,
  crossAxisSpacing: Common.w_12,
  mainAxisSpacing: Common.w_12,
  crossAxisCount: 3,
  maxUploadCount: 9,
  imgList: _imgList,
)),
```

* 效果
