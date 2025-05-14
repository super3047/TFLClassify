# 基于TensorFlow Lite实现的Android花卉识别应用
## 向应用中添加TensorFlow Lite

## 定位“start”模块MainActivity.kt文件的TODO 1，添加初始化训练模型的代码

## 对图像进行处理并生成结果，主要包含下述操作：
按照属性score对识别结果按照概率从高到低排序
列出最高k种可能的结果，k的结果由常量MAX_RESULT_DISPLAY定义



## 将识别的结果加入数据对象Recognition 中，包含label和score两个元素。后续将用于RecyclerView的数据显示

## 将原先用于虚拟显示识别结果的代码注释掉或者删除


## 最终结果展示
