# GeomertyReader Tips

**这是一个卡了我很久的东东，需要注意的是：**
GeometryReder应该放在视图的最外层，因为只有这样他才能获取到足够的空间尺寸，从而被它包入的view才能有尺寸，否则整个geometryreader这个View的frame size就是开始从父容器获得的尺寸，而不管里面的view的尺寸有多大