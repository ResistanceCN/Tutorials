<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [导出并分享规划](#%E5%AF%BC%E5%87%BA%E5%B9%B6%E5%88%86%E4%BA%AB%E8%A7%84%E5%88%92)
  - [一、电脑规划](#%E4%B8%80%E7%94%B5%E8%84%91%E8%A7%84%E5%88%92)
    - [1. 使用 DrawTools 插件规划好你想要的路线图](#1-%E4%BD%BF%E7%94%A8-drawtools-%E6%8F%92%E4%BB%B6%E8%A7%84%E5%88%92%E5%A5%BD%E4%BD%A0%E6%83%B3%E8%A6%81%E7%9A%84%E8%B7%AF%E7%BA%BF%E5%9B%BE)
    - [2. 右侧菜单中点击 `DrawTools Opt` 并使用 `Copy Drawn Items` 复制到剪贴板](#2-%E5%8F%B3%E4%BE%A7%E8%8F%9C%E5%8D%95%E4%B8%AD%E7%82%B9%E5%87%BB-drawtools-opt-%E5%B9%B6%E4%BD%BF%E7%94%A8-copy-drawn-items-%E5%A4%8D%E5%88%B6%E5%88%B0%E5%89%AA%E8%B4%B4%E6%9D%BF)
    - [3. 将这个文本以任意一种方式发送到你的手机上去](#3-%E5%B0%86%E8%BF%99%E4%B8%AA%E6%96%87%E6%9C%AC%E4%BB%A5%E4%BB%BB%E6%84%8F%E4%B8%80%E7%A7%8D%E6%96%B9%E5%BC%8F%E5%8F%91%E9%80%81%E5%88%B0%E4%BD%A0%E7%9A%84%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8E%BB)
    - [4. 手机上开启 `DrawTools Opt` 插件](#4-%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%BC%80%E5%90%AF-drawtools-opt-%E6%8F%92%E4%BB%B6)
    - [5. 侧边栏 `Info` 选项中 `Import Drawn Items` 从文件导入](#5-%E4%BE%A7%E8%BE%B9%E6%A0%8F-info-%E9%80%89%E9%A1%B9%E4%B8%AD-import-drawn-items-%E4%BB%8E%E6%96%87%E4%BB%B6%E5%AF%BC%E5%85%A5)
  - [二、手机规划](#%E4%BA%8C%E6%89%8B%E6%9C%BA%E8%A7%84%E5%88%92)
    - [1. 启用 `Bookmarks for maps and portals`](#1-%E5%90%AF%E7%94%A8-bookmarks-for-maps-and-portals)
    - [2. 左上角星标选择标记要连线的 Portal](#2-%E5%B7%A6%E4%B8%8A%E8%A7%92%E6%98%9F%E6%A0%87%E9%80%89%E6%8B%A9%E6%A0%87%E8%AE%B0%E8%A6%81%E8%BF%9E%E7%BA%BF%E7%9A%84-portal)
    - [3. `Info` 栏内 `Auto Draw` 两两选择 Portal 进行连接](#3-info-%E6%A0%8F%E5%86%85-auto-draw-%E4%B8%A4%E4%B8%A4%E9%80%89%E6%8B%A9-portal-%E8%BF%9B%E8%A1%8C%E8%BF%9E%E6%8E%A5)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## 导出并分享规划

### 一、电脑规划
> [DrawTools](https://iitc.modos189.ru/build/release/plugins/draw-tools.user.js)

#### 1. 使用 DrawTools 插件规划好你想要的路线图

![Plan](./images/plan.png)

#### 2. 右侧菜单中点击 `DrawTools Opt` 并使用 `Copy Drawn Items` 复制到剪贴板

![export](./images/export.png)

有 `json` 文本格式和生成链接两种导出形式

![export2](./images/export2.png)

建议直接新建一个 `.txt` 文件存储你复制的规划文本，当然如果规划不是复杂的话可以选择直接复制到剪贴板然后粘贴到手机上去

> 文本示例

```text
[{"type":"polygon","latLngs":[{"lat":23.062049,"lng":113.354463},{"lat":23.061924,"lng":113.354691},{"lat":23.061746,"lng":113.354825}],"color":"#a24ac3"},{"type":"polygon","latLngs":[{"lat":23.062049,"lng":113.354463},{"lat":23.062082,"lng":113.354881},{"lat":23.061746,"lng":113.354825}],"color":"#a24ac3"},{"type":"polygon","latLngs":[{"lat":23.062049,"lng":113.354463},{"lat":23.062082,"lng":113.354881},{"lat":23.061924,"lng":113.354691}],"color":"#a24ac3"},{"type":"polygon","latLngs":[{"lat":23.062082,"lng":113.354881},{"lat":23.061924,"lng":113.354691},{"lat":23.061746,"lng":113.354825}],"color":"#a24ac3"}]
```

#### 3. 将这个文本以任意一种方式发送到你的手机上去

#### 4. 手机上开启 `DrawTools Opt` 插件

![MobileDrawTools](./images/mobileDrawTools.jpg)

#### 5. 侧边栏 `Info` 选项中 `Import Drawn Items` 从文件导入

![ImportFromFile](./images/importFromFile.jpg)

导入效果如下

![Result](./images/Result.jpg)

### 二、手机规划

#### 1. 启用 `Bookmarks for maps and portals`

![MobileBookmarkTools](./images/mobileBookmarkTools.jpg)

#### 2. 左上角星标选择标记要连线的 Portal

![star](./images/star.jpg)

在 `Layer Chooser` 开启 `Bookmarked Portals`，标记效果如图

![Portals](./images/portals.jpg)

#### 3. `Info` 栏内 `Auto Draw` 两两选择 Portal 进行连接

![AutoDraw](./images/autoDraw.jpg)

完成效果如图，分享方式与电脑分享方式基本一致，有能力的话可以自己写一个 bot 或者 javascript 脚本帮助同步规划图，IITC 自带的 [Sync](https://iitc.modos189.ru/build/release/plugins/sync.user.js) 插件据部分用户反馈不可用，本文作者并未实测。

![Done](./images/done.jpg)