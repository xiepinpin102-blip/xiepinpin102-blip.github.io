# 犀牛共创地图 · GitHub Pages 静态版

入口文件是 `index.html`。

文件夹内已经包含：

- `index.html`：网站入口、样式和交互
- `rhino-cocreation-data.js`：项目与活动数据

## 发布到 GitHub Pages

1. 新建一个 GitHub 仓库。
2. 把这个文件夹里的全部文件上传到仓库根目录。
3. 在仓库的 **Settings → Pages** 中选择：
   - Source：Deploy from a branch
   - Branch：`main`
   - Folder：`/ (root)`
4. 保存后等待 GitHub Pages 生成网址。

## 说明

这是纯静态版本，不连接在线网站的后台数据库。因此：

- 看板内容可以正常浏览；
- 编辑和提交支持意向可以在当前浏览器中保存；
- 不同人的浏览器之间不会同步修改；
- 管理员删除支持意向功能不包含在这个静态版本中。

如果需要所有人同步看到修改，以及管理员统一删除支持意向，请继续使用在线版本：

https://rhino-cocreation-map.xiepinpin102.chatgpt.site/
