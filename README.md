# 配置
> ### list_config.json
>>list_config数据格式为数组，数组包含物品描述信息，排在前面的优先展示,
更新前需确保图片已上传resource目录。
>>```
>> 数据格式
>>"name":"物品名字",
>>"descr":"物品简短描述，可不写",
>>"detail":"物品详细描述，可不写",
>>"imageUrl":"https://raw.githubusercontent.com/TyouShare/mallConfig/master/resource/列表显示图片地址",
>>"mobile":"联系人手机号码，可不写",
>>"imageList":["https://raw.githubusercontent.com/TyouShare/mallConfig/master/resource/详情显示图片地址1","https://raw.githubusercontent.com/TyouShare/mallConfig/master/resource/详情显示图片地址2"]
>>```  

>### me.json
>> 个人信息页面配置，数据格式为字典。
>>```
>> 数据格式
>>"name":"名字",
>>"descr":"简介，可不写",
>>"avatar":"https://raw.githubusercontent.com/TyouShare/mallConfig/master/resource/头像",
>>"mobile":"联系人手机号码，可不写",

确保修改后文件为json格式，可先去校验格式是否正确。
[json 校验地址](http://www.bejson.com)
