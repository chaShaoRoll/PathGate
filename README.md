<div align="center">
  <img src="https://honguid.gallery.vsassets.io/_apis/public/gallery/publisher/honguid/extension/pathgate/latest/assetbyname/Microsoft.VisualStudio.Services.Icons.Default" alt="PathGate 图标" width="128">

  <h1>PathGate</h1>

  <p>
    在 VS Code 中集中管理常用文件与文件夹快捷入口。<br>
    <sub>Keep frequently used workspace resources one click away.</sub>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=honguid.pathgate"><img src="https://img.shields.io/visual-studio-marketplace/v/honguid.pathgate?style=flat-square&amp;label=VS%20Marketplace&amp;color=007acc" alt="VS Marketplace 版本"></a>
    <a href="https://marketplace.visualstudio.com/items?itemName=honguid.pathgate"><img src="https://img.shields.io/visual-studio-marketplace/i/honguid.pathgate?style=flat-square&amp;label=Installs&amp;color=4b8bbe" alt="安装量"></a>
    <a href="https://github.com/chaShaoRoll/PathGate/issues"><img src="https://img.shields.io/github/issues/chaShaoRoll/PathGate?style=flat-square&amp;color=6b7280" alt="GitHub Issues"></a>
    <img src="https://img.shields.io/badge/license-MIT-3d7a78?style=flat-square" alt="MIT License">
  </p>

  <p>
    <a href="#中文">中文</a>
    ·
    <a href="#english">English</a>
    ·
    <a href="https://github.com/chaShaoRoll/PathGate/issues">反馈问题</a>
  </p>
</div>

<a id="中文"></a>

## 中文

当工作区逐渐变大，常用文件往往散落在层层目录中。PathGate 允许你按自己的工作方式创建分组，把常用文件和文件夹集中到侧边栏或底部 Panel，而不需要移动或复制真实文件。

### 主要功能

- 创建、重命名、排序和清理快捷分组。
- 通过文件选择器、当前编辑器或 Explorer 拖放添加文件和文件夹。
- 为快捷项设置别名、搜索、筛选和置顶。
- 在分组内排序快捷项，或使用 `Ctrl` 多选后批量移动到其他分组。
- 保留暂时失效的路径，并在路径恢复或变更后重新定位。
- 单击文件快捷项进行预览，双击固定编辑器标签；也可将文件快捷项从 PathGate 拖入编辑区打开。
- 导出快捷配置，并安全合并导入其他工作区。
- 侧边栏和底部 Panel 共享快捷数据，同时保留各自的搜索、筛选和展开状态。

### 安装

在 VS Code 扩展视图中搜索 `PathGate`，或直接打开 [VS Marketplace 页面](https://marketplace.visualstudio.com/items?itemName=honguid.pathgate) 安装。

### 快速开始

1. 在 VS Code 中打开一个文件夹或工作区。
2. 从 Activity Bar 打开 PathGate，或显示底部 PathGate Panel。
3. 从 Explorer 将文件或文件夹拖入 PathGate，扩展会自动创建“默认组”；也可以先手动创建分组，再添加资源。
4. 单击文件快捷项进行预览，双击将标签固定在编辑区。右键快捷项可设置别名、置顶、移动或重新定位。

### 操作演示 / Demo

![PathGate 操作演示：将 Explorer 中的文件和文件夹拖入底部 Panel](resources/pathgate-demo.gif)

### 数据与安全

PathGate 将快捷配置保存在当前 VS Code 工作区的扩展存储中，不会在项目内创建配置文件。普通快捷操作不会创建、重命名、移动、复制或删除快捷项指向的真实文件，也不会发起网络请求。

只有在你主动执行“导出快捷项…”并在系统保存对话框中确认位置后，PathGate 才会写入所选的 JSON 文件；导入操作只读取你选择的 JSON，并更新当前工作区的快捷配置。

### 系统要求

- VS Code 1.95 或更高版本。
- 桌面版 VS Code。

### 反馈

如需报告问题或提出建议，请前往 [PathGate Feedback](https://github.com/chaShaoRoll/PathGate/issues)。

### 许可证

PathGate 按 MIT License 发布，完整许可证文本随扩展包提供。

<a id="english"></a>

## English

As a workspace grows, frequently used files tend to disappear into deeply nested folders. PathGate lets you organize shortcuts around your workflow and keep common files and folders in the Sidebar or bottom Panel—without moving or copying the actual resources.

> **Interface language:** The current PathGate interface and commands are available in Simplified Chinese.

### Features

- Create, rename, reorder, and clear shortcut groups.
- Add files and folders through pickers, the active editor, or drag and drop from Explorer.
- Assign aliases, search, filter, and pin shortcuts.
- Reorder shortcuts within a group, or hold `Ctrl` to select and move multiple shortcuts between groups.
- Keep temporarily unavailable paths and relink them after the resource returns or moves.
- Single-click a file shortcut to preview it, double-click to pin its editor tab, or drag it from PathGate into the editor area to open it.
- Export shortcut data and safely merge imports from another workspace.
- Share shortcut data between the Sidebar and Panel while keeping each view's search, filter, and expansion state independent.

### Installation

Search for `PathGate` in the VS Code Extensions view, or install it from the [VS Marketplace page](https://marketplace.visualstudio.com/items?itemName=honguid.pathgate).

### Quick Start

1. Open a folder or workspace in VS Code.
2. Open PathGate from the Activity Bar, or show the PathGate view in the bottom Panel.
3. Drag files or folders from Explorer into PathGate to create a “默认组” automatically. You can also create a group first and then add resources manually.
4. Single-click a file shortcut to preview it, or double-click to pin its editor tab. Right-click a shortcut to assign an alias, pin it, move it, or relink it.

### Data and Security

PathGate stores shortcut configuration in VS Code's extension storage for the current workspace and does not create configuration files inside your project. Normal shortcut operations do not create, rename, move, copy, or delete the referenced files, and they do not make network requests.

PathGate writes a JSON file only when you explicitly run “导出快捷项…” and confirm a location in the system save dialog. Import reads only the JSON file you select and updates the current workspace's shortcut configuration.

### Requirements

- VS Code 1.95 or later.
- Desktop VS Code.

### Feedback

Report issues or share suggestions at [PathGate Feedback](https://github.com/chaShaoRoll/PathGate/issues).

### License

PathGate is distributed under the MIT License. The full license text is included with the extension package.
