# auto_click
自动打卡

## userdata.json
为用户配置文件，即个人信息，根据个人情况进行更改
### 各参数解释:

<code>
  "uid": uid（网页打开后缀）每个人固定,
  
  "empid": id号（数字）每个人固定,
  
  "jrsfzx3": 是否在校（是/否）,
  
  "sheng": 省,
  
  "shi": 市,
  
  "xian": 区/县,
  
  "xxdz41": 详细地址,
  
  "sjh2": 手机号码,
  
  "gh": 学号,
  
  "xm": 姓名,
  
  "xb": 性别,
  
  "jinngdu": 地址经度,
  
  "weidu": 地址纬度,
  
  "email": 邮箱（便于通知打卡结果）
</code>
  
适用XUST健康打卡，填写各参数，运行即可打卡，可使用云函数托管，实现自动打卡
