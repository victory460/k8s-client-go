# k8s-client-go

一些调研k8s client-go用法的小demo

# 清单

// demo代码 github.com/owenliang/k8s-client-go地址
* common: 获取k8s配置文件
* demo1: 连接k8s
* demo2: 解析yaml为json, 反序列化到deployment对象, 修改deployment.spec.replicas, 提交到k8s生效
* demo3: 更新deployment.Spec.Template.Spec.Containers, 升级镜像版本, 提交到k8s生效
* demo4: 更新deployment, 循环获取部署状态, 判定部署完成, 并获取最新pod列表与失败原因
* demo5: xterm.js的基本用法, 为后续web ssh访问k8s container做铺垫
* demo6: xterm.js+client-go remotecommand实现完美web ssh登录container
* demo7: 获取POD内container的输出
* demo8: client-go的sdk日志配置
* demo9: 自定义CRD, 利用code generation生成controller骨架代码
* demo10: 实现一个类似于replicas的controller, 动态管理POD数量

* istio: 对DestinationRules Gateway ServiceEntry VirtualServices 的增删查更新操作
* gorest： 测试demo
* kubernetes： k8s相关测试
* test:  对crd 操作