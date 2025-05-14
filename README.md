# 基于TensorFlow Lite实现的Android花卉识别应用
## 向应用中添加TensorFlow Lite
![image](https://github.com/user-attachments/assets/e75541a5-f603-48a2-bd36-0a724ead38a7)

## 定位“start”模块MainActivity.kt文件的TODO 1，添加初始化训练模型的代码
![image](https://github.com/user-attachments/assets/200eea8c-d0fd-4f0b-bfb9-3747cc9e0a19)

## 对图像进行处理并生成结果，主要包含下述操作：
按照属性score对识别结果按照概率从高到低排序
列出最高k种可能的结果，k的结果由常量MAX_RESULT_DISPLAY定义
![image](https://github.com/user-attachments/assets/82a6f454-de63-4560-b9f9-55be2e6d1ec9)



## 将识别的结果加入数据对象Recognition 中，包含label和score两个元素。后续将用于RecyclerView的数据显示
![image](https://github.com/user-attachments/assets/1ffdd654-bba1-411e-bb98-8e8686cc0008)

## 将原先用于虚拟显示识别结果的代码注释掉或者删除
![image](https://github.com/user-attachments/assets/ef0569db-636b-43b7-9f4d-fc218636a57d)


## 最终结果展示
![Screenshot_20250514_102640_org tensorflow lite ex](https://github.com/user-attachments/assets/5067be7f-30a1-4546-944a-62a4a5f0832e)
