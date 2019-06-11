# 1.1创建git项目

在www.github.com进行注册，新建项目，如下图所示：![](/assets/import.png)目前mooplab暂只支持Public项目，后续会增加Private的支持。

项目中必须包含两部分内容：

```
1.notebook文件，如：example.ipynb
2.index.json   用于描述项目中的所有ipynb
```

index.json的格式如下：

```
{
    "labs": [
        {
            "example.ipynb": "示例1"
        }
    ]
}
```



