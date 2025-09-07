# 物理机 OS 装机脚本目录

本目录包含物理服务器操作系统（如 CentOS/Ubuntu）的自动化装机脚本，支持：
- 基础分区规划（/boot、/、swap 等）
- 基础软件预装（如 vim、net-tools）
- 网络接口初始化配置

使用说明：
1. 需提前准备 PXE 启动环境
2. 脚本参数通过 `config.yaml` 传入（见同级目录）
3. 执行命令：`bash os-install.sh --config=config.yaml`