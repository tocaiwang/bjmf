# -班级魔方部署腾讯云函数自动签到
班级魔法自动签到
通过将bjmf.zip压缩包上传到腾讯云函数并通过设置触发来实现每天的自动签到
根据[emocat17/BJMF](https://github.com/emocat17/BJMF)这位的源代码改的，具体用户配置（data.json里面设置）可以看这位大佬的，很详细。
打开https://cloud.tencent.com/search/%E4%BA%91%E5%87%BD%E6%95%B0%20SCF%20%E7%BB%84%E4%BB%B6/1_1
进入函数服务控制台，然后新建函数，点从头开始、python3.9、本地上传zip包、然后设置一下触发器就好了。
