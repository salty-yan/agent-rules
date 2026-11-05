# 项目约束与进度模板

统一管理本机和服务器使用的全局规则、项目规则与进度模板。

## 文件

1. [全局 AGENTS.md](global/AGENTS.md)：个人通用工作规则。
2. [项目 AGENTS.md 模板](templates/AGENTS.md)：项目入口、环境和特殊约束。
3. [YAN.md 模板](templates/YAN.md)：项目内容、进度、问题和下一步。

## 使用

1. 将 `global/AGENTS.md` 安装到运行 Codex 的机器上的 `~/.codex/AGENTS.md`；如设置了 `CODEX_HOME`，则放到该目录。登录同一个 Codex 账号不会自动复制本仓库中的文件。
2. 新项目将 `templates/AGENTS.md` 和 `templates/YAN.md` 复制到项目根目录，填写占位内容，删除不适用的条目。
3. 已有项目先合并现有规则和进度，再使用模板，保留项目已有信息。
4. 项目模板中的实验设计和结果链接只是示例，使用时替换为真实的项目相对路径。
5. 公共规则更新后，下载需要的版本再更新全局文件；项目模板用于初始化，后续更新按项目情况合并。

## 技能

全局规则要求的 `humanizer` 和 `karpathy-guidelines` 由现有的 [my-favor-skills 仓库](https://github.com/salty-yan/my-favor-skills) 维护。本仓库保存规则与模板，技能本体需另外安装。
