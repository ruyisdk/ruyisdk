---
name: 发版检查清单（Release CheckList）
about: 发版测试通过后的正式发版检查
title: "[发版] YYYY.MM - v版本号"
labels: [release]
---

## 1. 仓库/release 发版

每个链接为检查入口，请逐一打开核对后再勾选。

### ruyi 包管理器  @xen0n
检查入口：https://github.com/ruyisdk/ruyi/releases  
- [ ] 正式版本版本号
- [ ] 安装包
- [ ] 必要的变更描述

### ruyisdk-vscode-extension  @U2FsdGVkX1
检查入口：https://github.com/ruyisdk/ruyisdk-vscode-extension/releases
- [ ] 正式版本版本号
- [ ] 安装包
- [ ] 必要的变更描述

### ruyisdk-eclipse-plugins  @pzhlkj6612
检查入口：https://github.com/ruyisdk/ruyisdk-eclipse-plugins/releases
- [ ] 正式版本版本号
- [ ] 安装包
- [ ] 必要的变更描述

---

## 2. news

检查入口：https://github.com/ruyisdk/packages-index/tree/main/news

- [ ] ruyi  @xen0n
- [ ] ruyisdk-vscode-extension  @U2FsdGVkX1
- [ ] ruyisdk-eclipse-plugins  @pzhlkj6612
- [ ] 版本测试及遗留问题

---

## 3. 文档：文档仓库更新文档（新功能/新特性）

- 对照 changelog 进行核对和逐个沟通确认。
- 检查入口：https://github.com/ruyisdk/docs
- 说明：允许滞后完善，不阻塞发版。请在下方按本版本实际需要增减条目（每行一条）。

### ruyi 文档待办  @xen0n
- [ ] docs(ruyi):

### ruyisdk-vscode-extension 文档待办  @U2FsdGVkX1
- [ ] docs(ruyisdk-vscode-extension):

### ruyisdk-eclipse-plugins 文档待办  @pzhlkj6612
- [ ] docs(ruyisdk-eclipse-plugins):

---

## 4. 安装包多平台发布

### 发布到 mirror.iscas/ruyisdk  @xen0n
- [ ] ruyi：https://fast-mirror.isrc.ac.cn/ruyisdk/ruyi/
- [ ] ruyisdk-vscode-extension：https://fast-mirror.isrc.ac.cn/ruyisdk/ide/plugins/vscode/
- [ ] ruyisdk-eclipse-plugins：https://fast-mirror.isrc.ac.cn/ruyisdk/ide/plugins/eclipse/

### ruyi 发布到 pypi  @xen0n
- [ ] pypi ： https://pypi.org/project/ruyi/

### VSCode 插件发布到 openVSX 和 visualstudio marketplace  @U2FsdGVkX1
- [ ] openVSX：https://open-vsx.org/extension/RuyiSDK/ruyisdk-vscode-extension
- [ ] Visual Studio Marketplace：https://marketplace.visualstudio.com/manage/publishers/RuyiSDK

### Eclipse 插件发布到 Eclipse Marketplace  @pzhlkj6612
- [ ] Eclipse Marketplace：https://marketplace.eclipse.org/content/ruyisdk#metrics

---

## 5. 宣发与推送  @yuxizhang

- ruyisdk.cn 和 IM 渠道、wechat-articles 是默认的推送渠道；
- 参考 https://github.com/ruyisdk/packages-index/tree/main/news 对应版本文档；
- 允许弹性滞后，不阻塞发版。

**宣发（固定渠道）**  @yuxizhang
- [ ] 技术论坛：ruyisdk.cn
- [ ] IM 渠道推送
- [ ] RuyiSDK双周进展汇报： https://github.com/ruyisdk/wechat-articles

**宣发（更多途径）**  @xijing21
根据新特性决策更多宣发策略，请按需编辑（每行一条），提交后可逐行勾选。

- [ ] [宣发途径]-[系列]-[具体事项]
- [ ] [宣发途径]-[系列]-[具体事项]

---

## 6. 总结与遗留跟踪  @xijing21

请简要记录：
- 本次发版的关键成果与经验教训；
- 遗留问题、未完成事项及后续跟进；
- 需要在下一版本或下个周期解决的问题；
- 对协作流程的改进建议。

&lt;!-- 请在此填写 --&gt;
