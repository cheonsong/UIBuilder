## UIBuilder
The UIBuilder easily creates views through chaining.

### Bilder List
- [View](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/ViewBuilder.swift)
- [Button](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/ButtonBuilder.swift)
- [CollectionView](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/CollectionViewBuilder.swift)
- [CollectionViewFlowLayout](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/CollectionViewFlowLayoutBuilder.swift)
- [ImageView](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/ImageViewBuilder.swift)
- [Label](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/LabelBuilder.swift)
- [ScrollView](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/ScrollViewBuilder.swift)
- [StackView](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/StackViewBuilder.swift)
- [TextField](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/TextFieldBuilder.swift)
- [TextView](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/TextViewBuilder.swift)

### Usage

1. Create the desired Builder object
2. After setting properties
3. Returns UIView as a _view_ variable.  
(❗️layout: as a layout variable)

```Swift
  let view = ViewBuilder().backgroundColor(.white).view
  
  let button = ButtonBuilder().cornerRadius(10).title("Hello").view
  
  let label = LabelBuilder("Hello World!").font(~).textColor(.white).view
  
  let imageView = ImageViewBuilder(UIImage()).view
  
  ...
  
```

### Author

cheonsong, qkrcjsthd@gmail.com

### License

UIBuilder is available under the MIT license. See the LICENSE file for more info.
