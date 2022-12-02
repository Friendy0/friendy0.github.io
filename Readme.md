### 关于文件存放规范
- pages

    该文件夹存放的是要被嵌入的网页
- sources

    该文件夹存放的是您的数据
- static

    该文件存放的是静态数据如css、font、images、js、picture等
    
    特别的是：js中已经包含了d3, jquery, vega等的js，请编写时尽量用该处的（当然可以不用，只不过我强迫症犯了）
- index

    这是首页

    对于替换图片的方法就是搜索”iframe src=“就会找到这7处图片位置了，注意嵌入图片的尺寸。