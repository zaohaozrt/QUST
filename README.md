## 1.青岛科技大学教务系统挂机选课.py
#### cmd打开命令行输入chrome.exe --remote-debugging-port=9222 --user-data-dir="C:\selenum\AutomationProfile" （地址改为selenium对应的地址），自动打开浏览器，在浏览器中打开教务系统进入选课界面，并把选课界面标签页放到浏览器标签栏最左边位置，列表中课程编号换成自己要选的，运行程序，自动挂机选课。[具体使用方法](https://blog.csdn.net/nings666/article/details/134467103?spm=1001.2101.3001.6650.4&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EYuanLiJiHua%7EPosition-4-134467103-blog-89151988.235%5Ev40%5Epc_relevant_rights_sort&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EYuanLiJiHua%7EPosition-4-134467103-blog-89151988.235%5Ev40%5Epc_relevant_rights_sort&utm_relevant_index=9)
## 2.Python爬取教务系统课程表
  ### 版本1
  #### 搜索文件将“学号”二字换成自己的数字学号，将“密码”二字换成教务系统密码，form_data为请求参数，可以通过刷新教务系统课表界面抓包获取，一般一学期换一个，其他通用。
  ### 版本2
  #### 搜索文件将“学号”二字换成自己的数字学号，将“密码”二字换成教务系统密码，form_data为请求参数，可以通过刷新教务系统课表界面抓包获取，一般一学期换一个，其他通用。
## 3.Timetable
#### 青岛科技大学课表APP，可以直接运行，和上述类似，修改CourseDataBase文件中post_timetable函数参数即可，在登陆界面填写账号密码登录。
