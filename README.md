# yapi_php_py

#### 限制要求
```DOC
控制器类注释：
/**
  @api 【模块名字】 eg:xx模块
*/


控制器方法注释：
/**
 * 【方法中文名字】 eg:登录
 * @param int 【参数】eg:$user_name 【参数备注】eg:用户名字
 */

注：方法内不能存在/***/ 注释 可//注释
```

#### 具体设置

```comment
project_id：yapi项目对应的id值
token：yapi项目对应的token值
except：过滤文件用|作为分隔符带文件后缀
controller：请输入存放控制文件的文件的目录
except_dirs：过滤目录用|作为分隔符带文件后缀
以上均区分大小写

配置文件示例：
[Yapi]
project_id=
token=
except=
controller=
except_dirs=
```


##### 生成exe
```
http://www.pyinstaller.org/
pip install pyinstaller

pyinstaller -F xxx.py
```