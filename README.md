# Cherry Studio × Claude 主题

一套给 [Cherry Studio](https://github.com/CherryHQ/cherry-studio) 用的自定义 CSS 主题：深色玻璃 + 橙色高光，壁纸内嵌，不依赖任何本地文件。

## 效果

- 深色毛玻璃：侧栏、输入框、菜单、弹窗
- 壁纸铺满全屏，左侧压暗保证文字可读
- Tooltip 深底白字
- 输入框淡玻璃 + 橙色描边
- 资料预览、代码块、表格统一深色

## 安装

1. 打开 Cherry Studio → 设置 → 显示 → 自定义 CSS
2. 打开 `cherry-claude-theme.css`，全选复制
3. 粘贴进设置里的输入框，保存
4. 从托盘退出 Cherry Studio 再重新打开

## 说明

- 壁纸以 base64 内嵌在 CSS 里，文件约 1MB，属正常
- 主题里的毛玻璃（`backdrop-filter`）会占用显卡。低端核显可能出现风扇噪音或掉帧，介意的话可以把所有 `backdrop-filter` 行删掉
- 只适配浅色模式关闭、即深色模式下的 Cherry Studio

## 文件

| 文件 | 说明 |
| --- | --- |
| `cherry-claude-theme.css` | 完整主题（含壁纸） |

## 许可

MIT
