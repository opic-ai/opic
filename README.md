## 项目名称
OPIC （ Open Intelligence Computing） 开源智算项目

## 目录结构说明
以下为项目核心目录及文件列表，点击子目录名可跳转至对应子目录的 `README.md` 查看详情：

| 目录/文件路径                  | 类型       | 描述                                                                 |
|-------------------------------|------------|----------------------------------------------------------------------|
| `docs/`                       | 目录       | 文档中心 [查看详情](docs/README.md)                                   |
| `docs/architecture/`          | 目录       | 架构设计文档 [查看详情](docs/architecture/README.md)                  |
| `docs/deployment-guide/`      | 目录       | 部署指南 [查看详情](docs/deployment-guide/README.md)                  |
| `docs/network-design/`        | 目录       | 网络设计文档 [查看详情](docs/network-design/README.md)                |
| `docs/quick-start/`           | 目录       | 快速入门指南 [查看详情](docs/quick-start/README.md)                   |
| `docs/reference/`             | 目录       | 参考资料 [查看详情](docs/reference/README.md)                         |
| `scripts/`                    | 目录       | 核心脚本库 [查看详情](scripts/README.md)                              |
| `scripts/prelight/`           | 目录       | 基础设施准备 [查看详情](scripts/prelight/README.md)                   |
| `scripts/prelight/os-install/`| 目录       | 物理OS装机 [查看详情](scripts/prelight/os-install/README.md)          |
| `scripts/prelight/ssh-config/`| 目录       | SSH互信配置 [查看详情](scripts/prelight/ssh-config/README.md)          |
| `scripts/prelight/ntp-config/`| 目录       | NTP同步配置 [查看详情](scripts/prelight/ntp-config/README.md)          |
| `scripts/prelight/software-source/`| 目录   | 软件源配置 [查看详情](scripts/prelight/software-source/README.md)      |
| `scripts/prelight/dns-config/`| 目录       | DNS配置 [查看详情](scripts/prelight/dns-config/README.md)              |
| `scripts/k8s/`                | 目录       | K8S相关脚本 [查看详情](scripts/k8s/README.md)                         |
| `scripts/k8s/offline-install/`| 目录       | K8S离线安装 [查看详情](scripts/k8s/offline-install/README.md)          |
| `scripts/k8s/manifests/`      | 目录       | K8S资源清单 [查看详情](scripts/k8s/manifests/README.md)                |
| `scripts/k8s/configuration/`  | 目录       | K8S配置文件 [查看详情](scripts/k8s/configuration/README.md)            |
| `scripts/storage/deepseek-3fs/`| 目录      | DeepSeek 3FS部署 [查看详情](scripts/storage/deepseek-3fs/README.md)     |
| `scripts/rdma/`               | 目录       | RDMA组网脚本 [查看详情](scripts/rdma/README.md)                       |
| `scripts/rdma/switch-config/` | 目录       | 交换机配置 [查看详情](scripts/rdma/switch-config/README.md)            |
| `scripts/rdma/server-config/` | 目录       | 服务器RDMA配置 [查看详情](scripts/rdma/server-config/README.md)        |
| `scripts/rdma/qos-config/`    | 目录       | QoS配置 [查看详情](scripts/rdma/qos-config/README.md)                  |
| `scripts/gpu/`                | 目录       | 国产卡相关脚本 [查看详情](scripts/gpu/README.md)                      |
| `scripts/gpu/driver-install/` | 目录       | 驱动安装 [查看详情](scripts/gpu/driver-install/README.md)              |
| `scripts/gpu/k8s-device-plugin/`| 目录      | 设备插件 [查看详情](scripts/gpu/k8s-device-plugin/README.md)           |
| `scripts/gpu/node-exporter/`  | 目录       | 监控插件 [查看详情](scripts/gpu/node-exporter/README.md)               |
| `scripts/logging/`            | 目录       | 日志系统部署 [查看详情](scripts/logging/README.md)                    |
| `configs/`                    | 目录       | 配置文件库 [查看详情](configs/README.md)                              |
| `configs/network/`            | 目录       | 网络配置 [查看详情](configs/network/README.md)                        |
| `configs/container-registry/` | 目录       | 镜像仓库配置 [查看详情](configs/container-registry/README.md)          |
| `configs/offline-sync/`        | 目录       | 离线同步配置 [查看详情](configs/offline-sync/README.md)                |
| `configs/k8s/`                | 目录       | K8S配置文件 [查看详情](configs/k8s/README.md)                          |
| `manifests/`                  | 目录       | 资源清单库 [查看详情](manifests/README.md)                            |
| `manifests/k8s-components/`   | 目录       | K8S组件清单 [查看详情](manifests/k8s-components/README.md)             |
| `manifests/deepseek-3fs/`      | 目录       | DeepSeek 3FS清单 [查看详情](manifests/deepseek-3fs/README.md)          |
| `manifests/logging/`          | 目录       | 日志系统清单 [查看详情](manifests/logging/README.md)                  |
| `examples/`                   | 目录       | 示例库 [查看详情](examples/README.md)                                 |
| `examples/small-cluster/`     | 目录       | 小型集群示例 [查看详情](examples/small-cluster/README.md)              |
| `examples/medium-cluster/`    | 目录       | 中型集群示例 [查看详情](examples/medium-cluster/README.md)             |
| `examples/large-production/`  | 目录       | 大型生产集群示例 [查看详情](examples/large-production/README.md)       |
| `tools/`                      | 目录       | 辅助工具库 [查看详情](tools/README.md)                                |
| `tools/network-check/`        | 目录       | 网络检测工具 [查看详情](tools/network-check/README.md)                |
| `tools/hardware-check/`       | 目录       | 硬件检测工具 [查看详情](tools/hardware-check/README.md)               |
| `tools/cluster-status/`       | 目录       | 集群状态检查 [查看详情](tools/cluster-status/README.md)               |
| `LICENSE`                     | 文件       | 开源许可证（Apache 2.0）                                             |
| `CONTRIBUTORS.md`             | 文件       | 项目贡献者列表                                                       |
| `CHANGELOG.md`                | 文件       | 版本更新记录                                                         |
        