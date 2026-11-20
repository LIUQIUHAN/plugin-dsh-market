<h1 align="center">DSH 插件市场索引</h1>

<p align="center">DeepSeek Harness 社区插件索引 · Community plugin index for DeepSeek Harness</p>

<p align="center"><code>plugin-dsh-market/index.json</code></p>

## 使用方法 · How to use

1. 安装官方实验包 **Plugin market**（`@deepseek-ai/dsh-experimental-plugin-market-bundle`）：Plugins → 可选插件 → Plugin market。
2. 在同一页的插件市场设置里，把下面的索引地址加入索引列表：
   `https://raw.githubusercontent.com/LIUQIUHAN/plugin-dsh-market/main/index.json`
3. 打开 **Discover** 页搜索插件，点安装。

1. Install the official **Plugin market** bundle (`@deepseek-ai/dsh-experimental-plugin-market-bundle`).
2. Add the index URL above to its configured index list.
3. Search on the **Discover** page and install.

## 收录的插件 · Plugins

| 包名 · Package | 说明 · Description |
|---|---|
| [`@dsh2030/session-delete`](https://github.com/LIUQIUHAN/session-delete) | 在侧边栏永久删除会话，包括正在打开或正在运行的会话。Permanently delete sessions, including the open or running one. |

## 索引格式 · Index format

`index.json` 使用 DSH 插件市场索引 **format 1**：顶层 `format`、`title`、可选 `description` 与 `metadata`，以及 `plugins[]`，每个插件含 `name`、`title`、`description`、`icon`、`versions[]`；每个版本指明安装来源（`npm` 或 `git`，git 需固定 40 位 commit）。本仓库的 `schema/` 目录放了示例与字段说明，供新插件登记参考。
