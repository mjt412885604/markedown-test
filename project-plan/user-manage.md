# 运营后台-用户管理


## 说明
为了提升用户端APP整体易用性，进行UI改版、原有功能和使用流程优化，同时新增部分功能以更好的满足用户诉求。

## git仓库
- 项目名称：PanderOperate
- git@code.aliyun.com:pddwebclient/PanderOperate.git

## 技术架构
> React + React-Router + React-rudex + antd + Wbbpack

## 产品参与人
- 产品：韩伟光
- 服务端：待定
- WEB端：马啸天

## ESlint代码检测
本项目引入ESlint代码检测工具，请开发人员遵守具体的规则进行编写已提高代码的质量。
例如：

```javascript
"no-multi-spaces": 1,
"jsx-quotes": 1,
"no-undef": 2, //不能有未定义的变量
"no-const-assign": 2, //禁止修改const声明的变量
"no-delete-var": 2, //不能对var声明的变量使用delete操作符
"no-dupe-keys": 2,//在创建对象字面量时不允许键重复 {a:1,a:1}
"no-dupe-args": 2,//函数参数不能重复
"no-duplicate-case": 2,//switch中的case标签不能重复
"no-func-assign": 2,//禁止重复的函数声明
"no-invalid-regexp": 2,//禁止无效的正则表达式
"no-multiple-empty-lines": [1, { "max": 2 }],//空行最多不能超过2行
"default-case": 2,//switch语句最后必须有default
```

## 代码规范
1. 项目文件语义化。
2. 项目代码易读性要强，面向对象编程思维编程，关键位置表明注释。
3. 项目尽量模块化，分类性要强。
4. 项目引用插件要是稳定的、在维护性的、大场的最号，能手写的插件尽量手写。
5. 小图片尽量合并或者转码，减少网络请求量。
6. 移动端css布局尽量使用`flex`布局加大开发效率。
7. js使用`es6`编码方式加大开发效率。
8. 使用`Promise`,`Object`, `async、await`要进行编译为ES5的支持，避免出现兼容问题。
9. git代码提交要`commit`一下此次提交的改动内容。
10. git不允许在`master`上面开发，最新的代码需要个人负责的项目结束后合并到`master`分支上。
11. 减少git分支过多的创建，每次个人负责的项目开发完毕后删除多余的`git分支`，保持git分支的整洁性。

## 项目排期
项目排期分为页面编写与接口联调

### 静态页面编写
| 模块 | 功能 | 负责人 | 周期（h）| 提测时间 | 服务端 | 产品 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 订单管理 | 订单管理列表 | 马啸天 | 3 | 2018-11-20 |  | 韩伟光 |
| 订单管理 | 订单详情(图文+快速) | 马啸天 | 3 | 2018-11-20 |  | 韩伟光 |
| 订单管理 | 订单详情-电话 | 马啸天 | 2 | 2018-11-20 |  | 韩伟光 |
| 订单管理 | 订单详情-预约挂号 | 马啸天 | 3 | 2018-11-20 |  | 韩伟光 |
| 订单管理 | 订单详情-健康卡 | 马啸天 | 2 | 2018-11-20 |  | 韩伟光 |
| 订单管理 | 退款审批列表 | 马啸天 | 3 | 2018-11-20 |  | 韩伟光 |
| 订单管理 | 退款详情 | 马啸天 | 3 | 2018-11-20 |  | 韩伟光 |
| 评价管理 | 评价管理列表 | 马啸天 | 3 | 2018-11-20 |  | 韩伟光 |
| 评价管理 | 评价详情 | 马啸天 | 4 | 2018-11-20 |  | 韩伟光 |
| 医生信息管理 | 列表 | 马啸天 | 4 | 2018-11-20 |  | 韩伟光 |
| 医生信息管理 | 医生详情 | 马啸天 | 4 | 2018-11-20 |  | 韩伟光 |
| 医生信息管理 | 电话咨询设置 | 马啸天 | 3 | 2018-11-20 |  | 韩伟光 |
| 医生信息管理 | 预约挂号配置 | 马啸天 | 3 | 2018-11-20 |  | 韩伟光 |
| 合计 |  |  | 40 |  |  |  |

### 接口联调
>计划7天的工时

## 谨记
```text
最初的90%的代码用去了最初90%的开发时间。余下的10%的代码用掉另外90%的开发时间。
```