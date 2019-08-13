仓库需处理的问题说明：
| 敏感源                          | 敏感原因             | 处理方法                                |
| ------------------------------- | -------------------- | --------------------------------------- |
| sdflysha@qq.com                 | 个人邮箱签入公司项目 | 替换为“公司”邮箱：sdflysha@starworks.cc |
| 文件Program.cs                  | AWS Key保存在文件    | 替换将AWS Key为：REPLACED               |
| 文件appsettings.Production.json | 生产环境配置文件     | 删除                                    |
| 文件夹userSecrets               | 用户相关帐号等       | 删除                                    |
| Program.exe                     | 大二进制文件签入     | 删除                                    |