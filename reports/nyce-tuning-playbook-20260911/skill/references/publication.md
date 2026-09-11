# 报告发布与历史保全

本项目已有公开站：https://zhengpengzhengpeng447-arch.github.io/nyce-reports/ 。用户指定该站时继承会话已有公开授权，不另建无关托管站。

本地reports.json位于report_site/，report_site/site/是独立Git仓库，Pages历史配置为main根目录；以后发布先核当前配置。

先生成可审查静态报告。新方案写明待验证，不能混成新实测。仅选择文档、图表、汇总和必要参数，不递归复制data、完整聊天、登录脚本、本机服务地址或控制器工具。

新报告用新目录，冻结旧reports文件hash。旧build.py会重建全部报告且首页日期曾写死，应采用追加或逐项审查，避免静默改旧页。验证相对链接、窄屏显示、下载内容；无法公开的证据注明保存在实验档案，不伪造网址。

检查git diff，仅提交本轮授权内容，不force push。等Pages部署后以无登录HTTP核对新页/资产hash和旧关键页；区分提交、部署和公开可访问。

公开skill保持相对references完整，不含绝对用户路径、登录参数或密钥。日期基准只是复现记录，不是安装后自动执行的配置。
