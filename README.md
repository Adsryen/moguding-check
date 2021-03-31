# moguding-check
Python脚本实现蘑菇丁的自动签到
由于蘑菇丁只有app能签到

因为有个签到的数据ID无法确定是唯一的，大家还是学下怎么抓包吧

需要的工具和环境：
蘑菇丁app
抓包工具
python环境

在签到的时候进行抓包，
记录好url、head头部和post数据，和实习打卡的经纬度与街道，后面要用python实现脚本登陆

返回大概这样的东西

{
  "country": "中国",
  "address": "中国四川省XXXXXXXXXXXXXXXXXXXXX",
  "province": "四川省",
  "city": "XXXX市",
  "latitude": "xx.xxxxxx",#经度
  "description": "",
  "planId": "fe83297618b2d4cdee4fb7e296fb5de3",
  "type": "END",
  "device": "Android",
  "longitude": "xxx.xxxxxx"#纬度
}

填入py代码   部署云函数 或者win10计划任务   或者服务器定时run py  搞定
