数据来源：
https://www.sojson.com/blog/305.html
调用的Api：
http://t.weather.sojson.com/api/weather/city/101010800
api更新时间：
3点,8点,13点,19点，建议不要凌晨去获取，加上CDN有1个小时的缓存，建议4点,9点,14点,20点后获取。
后面的数字为城市编号。城市编号脚本如下，其中有重复的url，同一地区不同的地方对应相同的url和城市编码。在代码中进行了去重。
