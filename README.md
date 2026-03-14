# DIYP
Do It Yourself Player（自定义你的播放器）

一、DIYP影音经典版、Final版、DIYP一代及使用教程合集
https://www.right.com.cn/forum/thread-8280295-1-1.html
一直被模仿，从未被超越！
软件下载地址：
DIYP影音经典版（部分闪退）：https://diyp.lanzoub.com/ia1Ojlcwhah
DIYP影音Final版（不闪退）：https://diyp.lanzoub.com/izJX1kmgsfg
DIYP一代（简洁播放器）：https://diyp.lanzoub.com/ikFJ2kif0le
软件使用教程：
【DIYP影音】使用教程：http://www.360doc.com/content/20/0520/16/58007313_913511325.shtml
【DIYP影音】自定义背景教程：http://www.360doc.com/content/20/0521/16/58007313_913714396.shtml
对象存储OSS管理IPTV节目源：http://www.360doc.com/content/20/0522/17/58007313_913926157.shtml
码云gitee托管IPTV节目源教程：http://www.360doc.com/content/20/0522/22/58007313_913971929.shtml
EPG自定义使用教程，感谢原作者@aming.ou：https://www.right.com.cn/forum/thread-8315423-1-1.html
附：
①DIYP一代使用教程（word）版：https://diyp.lanzoub.com/b0dz4da4f 密码:cyrj
②DIYP影音软件使用教程（word版）：https://diyp.lanzoub.com/b0dz4d8fe 密码:7fuv
注：码云、OSS管理节目源可能有出入，大家自行摸索！
纯空壳播放器一个，无流传后门之说！魔改版本人不知！

二、DIYP影音利用php空间管理直播源（优于单个文档内多个分类）
https://www.right.com.cn/forum/thread-8318999-1-1.html
前提：有php空间（云虚拟主机、手机KsWeb环境）
一、把list.php文件上传至wuji.diyp.top文件目录下，并在其目录下新建“list”文件夹！
二、把分类好的直播源txt文档上传至“list”文件夹里，可存放n个文档，可自动读取！（注意：保存文档格式为UTF-8）
三、访问地址（示例）：http://wuji.diyp.top/list.php
四、文件下载地址：https://share.weiyun.com/2Tb67pYV

三、DIYP影音节目加密设置教程（仅供娱乐研究）
https://www.right.com.cn/forum/thread-8319361-1-1.html
只需在分类后面加英文下划线+密码即可“_123456”，如下：
加密节目_123456,#genre#
10003,http://gcalic.v.myalicdn.com/gc/hswlf_1/index.m3u8

四、DIYP影音回看通过开启时移进行快进快退
https://www.right.com.cn/forum/thread-8352677-1-1.html
路径：设置—>偏好设置—>开启时移
开启时后回看可快进快退（支持遥控）

五、安卓盒子利用KSWEB搭建EPG服务器，DIYP影音测试可正常运行！
https://www.right.com.cn/forum/thread-8352749-1-1.html
非常感谢：@aming.ou的无私奉献和各位大神的EPG采集，让DIYP影音焕发生机！
EPG使用请参考教程：https://www.right.com.cn/forum/thread-8315423-1-1.html
注：有条件的坛友可自行搭建，无条件的坛友可在网上搜索别人分享的EPG链接！
附：list频道列表批量管理（只需更改A列频道名，B列频道id无需修改），N—>1!
如：CCTV1/CCTV-1/CCTV1高清/CCTV-1高清，均可指向频道id  cctv1获取到EPG！
注：批量编辑好后只需全选SQL列的数据复制粘贴导入epg_channel中SQL中即可！
温馨提示：安卓电视盒子可以安装KSWEB环境后在htdocs目录下存放此脚本运行！
局域网用电脑或手机采集EPG示例（http://192.168.1.11:8088/diyp/xml2db.php）
DIYP影音“EPG接口”处填写地址示例（http://192.168.1.11:8088/diyp/epg.php）
安卓手机/盒子安装KSWEB环境参考教程：https://post.smzdm.com/p/az6qk4er/
KSWEB官网地址：https://kslabs.ru/download（注意：安卓系统请下载arm版本）
亲测环境安卓盒子，php版本7.3.30，xml2db.php脚本支持“计划任务”定时采集！
KSWEB计划任务→编辑任务→选“执行控制台命令”→选择控制台脚本xml2db.php
注意：控制台脚本要存放在htdocs目录下的diyp文件夹里，勾选“使用root权限”！
Cron表达式（0 */59 ***?），表示每59分钟采集一次，填写括号里的内容即可，
更多表达式请参考：https://blog.csdn.net/CoderTnT/article/details/128844599
安卓盒子开机后先运行KSWEB，支持开机自启功能的盒子把KSWEB加入自启项！
注：24小时开启的盒子才会自动采集，若每次开启则要到任务计划点才能采集！
手机电脑同一局域网浏览器访问http://192.168.1.11:8088/diyp/xml2db.php采集！

六、DIYP影音、酷9专用EPG
https://www.right.com.cn/forum/thread-8461592-1-1.html
①http://diyp.fans/diyp/epg.php（优先推荐）
②http://20f1c95954.qicp.vip/diyp/epg.php（测试线路）
③http://201v95954g.vicp.fun/diyp/epg.php（测试线路）
注：②③开放时间段（部署在Nas）：08:30-23:30

七、DIYP影音升级版（基于TVBOX二次开发）
https://www.right.com.cn/forum/thread-8463477-1-1.html
DIYP影音升级版（基于TVBOX源码二开）。
DIYP影音升级版：
https://diyp.lanzoue.com/b034186lqb
密码:diyp
其它高阶玩法：
酷9：
https://wfy.lanzout.com/b0izqfjwb
密码:123456
极致：
https://wwam.lanzoub.com/b00efneg4d
密码:jizhi
