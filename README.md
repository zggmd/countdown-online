# countdown-online
一个挂着灯笼🏮的倒计时网页
线上 demo： https://encode.zggmd.com/countdown-online/
# 配置
支持通过自定义url query 参数配置页面:

| 参数    | 说明                                                     | 默认值         |
|-------|--------------------------------------------------------|-------------|
| l1    | 左边的灯笼的文字                                               | 春           |
| l2    | 右边的灯笼的文字                                               | 节           |
| title | 网页title和网页内的标题                                         | 春节放假倒计时     |
| time  | 截至时间, 格式为 YYYY-MM-DDTHH:mm:ss , 例如 2024-02-10T19:00:00 | 默认为当天的18:00 |

举例:
https://encode.zggmd.com/countdown-online?l1=国&l2=庆&title=国庆放假倒计时&time=2024-10-01T00:00:00
