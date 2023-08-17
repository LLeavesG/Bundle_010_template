# Bundle_010_template

This is an experimental template for parsing serialized bundle binary data in 010 Editor. 

这是一个在010editor上解析bundle序列化二进制数据的实验性模板

The template implements the parsing of Bundle serialized data. The parsing supports most common data formats and is used for Android development or security research work.

模板实现了对Bundle序列化数据的解析，解析支持大部分常用的数据格式，用于Android开发或安全研究工作

PS：If there is Parcelable data, you need to modify the offset of the number of Parcelable values in the serialized data in the bt file (considering the length of BundleLength and the magic word of 8 bytes) and the length of the data (in order).

PS: 如果存在 Parcelable 类型数据 需要修改bt文件中的序列化数据中 Parcelable 类型值的 个数 偏移(需考虑BundleLength 和 魔术字共8字节) 以及 数据长度(按顺序)

![image](https://github.com/LLeavesG/Bundle_010_template/assets/57952228/80760345-eb8e-48d8-82fe-9f0565f5a0ec)
