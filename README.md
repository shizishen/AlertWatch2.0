# AlertWatch2.0
The network camera uploads the surveillance video to the SRS streaming server in real time, and the cloud GPU server pulls the original video stream for inference. The client accepts the original video stream as well as the inference results
![Screenshot_20231214_155653](https://github.com/shizishen/AlertWatch2.0/assets/85082613/af40046e-f87a-4654-ac56-bab1c74168b2)

# 流程图以及进程
##  App推流                ✓   
##  海康威视摄像头推流  
      |  
      |  
      |  
    服务器开发  
        |  
        ---srs-rtmp       ✓   
        |  
        ---视频推理脚本       
        |  
        ---数据库设计  
      |  
      |  
      |  
    管理员开发  
    安卓用户开发            ✓   
