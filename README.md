重庆大学明月科创实验班软件设计大作业“ROS数据展示系统”演示视频。
一，任务内容
利用松灵小车上录制的bag包数据（从QQ群下载），编写软件，展示ROS系统中的各类数据，具体包括：
用命令行窗口显示小车的IMU和里程计（odometry）数据;
用图形界面显示颜色相机和深度相机的数据（利用OpenCV库）;
用图形界面显示激光雷达的点云数据（利用PCL库）;
自行选择一种高级算法（例如语义分割、三维重建、导航定位（SLAM）等），实现该算法（可以直接利用第三方库），将其集成到系统中。

二，代码要求
所有程序代码采用C++编写，使用git进行源代码管理;
类名、变量名、函数名应符合C++的命名规范，并在代码中前后保持一致;
涉及面向对象的程序，例如自定义的类，应符合面向对象的设计原则;
正确使用头文件和源文件，自定义的头文件应符合头文件的编写原则，例如用条件宏定义确保头文件不被多次引用、不在头文件中进行类和函数的实现（模板除外）;
项目必须是ROS项目，符合ROS的项目的规范，正确编写CmakeLists.txt等文件;

三，提交资料
程序源代码，需要包含git仓库（.git文件夹），源代码需上传到公网上的git仓库，并提供仓库的URL地址;
录制程序的演示视频，视频可以传到B站，上传视频播放的URL地址;
提交一份报告，描述程序实现的关键步骤、算法和结果;

四，成绩构成
代码规范性占10分;
git的使用占10分;
报告和视频占20分;
任务1-3占50分;
任务4占10分；
