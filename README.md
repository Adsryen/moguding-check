# moguding-check
Python脚本实现蘑菇丁的自动签到<br>
由于蘑菇丁只有app能签到<br>
因为有个签到的数据ID无法确定是唯一的，大家还是学下怎么抓包吧<br>

需要的工具和环境：<br>
蘑菇丁app<br>
抓包工具<br>
python环境<br>
<br>
在签到的时候进行抓包，<br>
记录好url、head头部和post数据，和实习打卡的经纬度与街道，后面要用python实现脚本登陆<br>
<br>
返回大概这样的东西<br>
<br>
{<br>
  "country": "中国",<br>
  "address": "中国四川省XXXXXXXXXXXXXXXXXXXXX",<br>
  "province": "四川省",<br>
  "city": "XXXX市",<br>
  "latitude": "xx.xxxxxx",#经度<br>
  "description": "",<br>
  "planId": "fe83297618b2d4cdee4fb7e296fb5de3",#planID<br>
  "type": "END",<br>
  "device": "Android",<br>
  "longitude": "xxx.xxxxxx"#纬度<br>
}<br>
<br>
填入py代码   部署云函数 或者win10计划任务   或者服务器定时run py  搞定<br>
