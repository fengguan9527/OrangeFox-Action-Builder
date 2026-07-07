# OrangeFox Action Builder

**这是一个基于 GitHub Actions 的自动化编译脚本，专门用于编译 OrangeFox Recovery。该版本已加入对16.0的全新支持，并针对最新的编译同步策略（包含特定的 sync 仓库以及震动补丁逻辑）进行了深度优化。**

### ​如何使用
**​Fork 本仓库到你的个人 GitHub 账号下。**

**​在你 Fork 的仓库中，前往 Actions 标签页。**
(如果提示 Actions 未启用，请点击绿色按钮允许其运行)。

**​在左侧菜单中选择 OrangeFox - Build 流程，然后点击右侧的 Run workflow 下拉菜单，填写你的设备参数**：

# 参数名称填写
 -**MANIFEST_BRANCH**：可选 16.0 、12.1 或 11.0。
 
 -**DEVICE_TREE**：设备树仓库链接，你的 Recovery 设备树 Git 地址。
 
 -**DEVICE_TREE_BRANCH**：你设备树默认分支名。

 -**DEVICE_PATH**：设备树存放路径，在源码树中的绝对路径。
 
 -**DEVICE_NAME**：例如你的设备代号。
 
 -**LUNCH_TARGET**：编译目标，执行 lunch 命令时的完整目标名称。
 
 -**BUILD_TARGET**：编译生成物，可选 recovery、boot 或 vendorboot。
