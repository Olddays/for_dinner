# for_dinner
部门新来了个同事，负责视频编导和制作。经常需要使用Premiere渲染视频，这是一项十分费时的工作，动辄3-4个小时。

同事时常在傍晚4-5点开始渲染视频，待其完成，将渲染好的视频发送出去，再关闭电脑回家。这样一来，往往就到晚上9/10点了。

这样一来，就没空做晚饭和次日的便当了，念其厨艺棒极，为了午饭时间能闻到土豆炖牛肉的香味，我决定写个脚本完成这个工作。

#任务描述
该脚本监控视频导出目录，发现视频文件生成时，将其同步到云盘，同步完成后给相关人员发送邮件，通知其下载。此后关机。

#使用
*  pip install -r requirements.txt
*  配置./config.py
*  bypy.py info 根据提示做相应配置
*  python for_dinner.py
