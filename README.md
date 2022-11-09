## UIBuilder
The UIBuilder helps you create views easily.

### Bilder List
- [View](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/View.swift)
- [Button](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/Button.swift)
- [CollectionView](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/CollectionView.swift)
- [CollectionViewFlowLayout](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/CollectionViewFlowLayout.swift)
- [ImageView](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/ImageView.swift)
- [Label](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/Label.swift)
- [ScrollView](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/ScrollView.swift)
- [StackView](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/StackView.swift)
- [TextField](https://github.com/cheonsong/UIBuilder/blob/master/UIBuilder/TextField.swift)

### Usage

1. Create the desired Builder object
2. After setting properties
3. Returns UIView as a _view_ variable

```Swift
  let view = View().backgroundColor(.white).view
  
  let button = Button().cornerRadius(10).title("Hello").view
  
  let label = Label("Hello World!").font(~).textColor(.white).view
  
  let imageView = ImageView(UIImage()).view
  
  ...
  
```
