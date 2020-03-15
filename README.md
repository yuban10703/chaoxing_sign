# chaoxing_sign
## API   
签到 https://mobilelearn.chaoxing.com/pptSign/stuSignajax?activeId=xxx&uid=xxx&clientip=&latitude=-1&longitude=-1&appType=15&fid=0  
获取课程 https://mobilelearn.chaoxing.com/ppt/activeAPI/taskactivelist?courseId=xxx&classId=xxx&uid=xxx  
获取活动列表 http://mooc1-api.chaoxing.com/mycourse/backclazzdata?view=json&rss=1  

任务|请求方式  | 参数  | Cookie |  注意
 -----|---- | ----- | ------ |----- 
 签到|GET  | activeId，uid |  √|返回success为签到成功，失败可能是更新状态延迟|
 获取课程|GET  | courseId，classId，uid  | √|activeType=2 且 status=1 就为未签到活动 |
 获取活动列表|GET  | 无 | √ | |
 ## 使用  
 在脚本内填入学习通账号密码即可自动签到。  
 代码修改自B站up主UID:85497962。原作者：@[一碗炒饭啊](https://www.bilibili.com/video/av94208525 )  
 修改内容：使用账号密码登录，自动获取cookie,uid。
 
