# 蓦然
“蓦然”App  是一个基于地理位 置的周边环境采集、发现、评论社区。使 用“蓦然”，用户可以对周边环境（建筑、 景点、街道、商铺….  ）进行拍照，并发表 评论。也可以查看其他用户对周边环境拍 摄的照片和评论。 

# 命名约定
* 包的命名
    * 按模块进行分类
* 类和接口命名
    * 文件命名：功能+分类 BaseActivity、ToastUtil
* View层的命名
    * 控件命名：控件_范围_功能 edit_login_password
* 问题R.string命名
    * 页面标题，命名格式为：title_{页面}
    * 按钮文字，命名格式为：btn_{按钮事件}
    * 标签文字，命名格式为：label_{标签文字}
    * 选项卡文字，命名格式为：tab_{选项卡文字}
    * 消息框文字，命名格式为：toast_{消息}
    * 编辑框的提示文字，命名格式为：hint_{提示信息}
    * 图片的描述文字，命名格式为：desc_{图片文字}
    * 对话框的文字，命名格式为：dialog_{文字}
    * 其他提示信息，命名格式为：error_{文字}/success_{文字}


## 0.1.0
1. 完成基础活动页，登陆页面
2. 完成自定义提示框制作，基本测试无问题
3. 完成一些信息配置

## 0.2.0
1. 修复自定义dialog的bug
2. 完成login
3. StringUtil和ToastUtil工具类完成
4. 完成命名约定