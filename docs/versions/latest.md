---
sidebar_position: 99
---

# 最新版本

更新于：2025-06-09

:::tip 护甲+1

import DayCounter from '@site/src/components/DayCounter';

音流发布至今已有 <DayCounter dateStr="2023-06-06"/> 天了，共更新了 38 个版本，还是个很年轻的播放器呢～

因个人开发经验与精力所限，且要兼顾多个平台与音乐服务，更新速度与 bug 解决速度难免要慢一些，望诸君见谅。

但我始终相信：下个版本会更好！

:::

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import Button from '@mui/material/Button';
import WindowIcon from '@mui/icons-material/Window';
import AppleIcon from '@mui/icons-material/Apple';
import AndroidIcon from '@mui/icons-material/Android';

## V1.3.8（2025-06-09）

<Tabs groupId="operating-systems">
<TabItem value="android" label="Android">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} target="_blank" href="https://wwco.lanzouq.com/b00jegk50b">立即下载</Button>
</div>
</TabItem>

<TabItem value="win" label="Windows">

推荐直接在[微软应用商店](https://apps.microsoft.com/detail/9ng5zw78qc1s)安装，或通过下方按钮手动安装。

<div class="mv-sm">
    <Button variant="contained" startIcon={<WindowIcon />} target="_blank" href="https://www.ilanzou.com/s/sfhZVFga">立即下载</Button>
</div>

:::caution

从 1.3.8 开始，Windows 版本更换了证书文件，若安装失败请查看[安装教程](/docs/guides/install)

:::
</TabItem>

<TabItem value="mac" label="macOS">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AppleIcon />} target="_blank" href="https://www.ilanzou.com/s/asxZVZoH">立即下载</Button>
</div>
</TabItem>
</Tabs>

更新内容:

- [部分歌单顺序播放时允许超出 500 首的队列上限](https://github.com/gitbobobo/StreamMusic/issues/772)
- [添加到歌单时提供去重选项](https://github.com/gitbobobo/StreamMusic/issues/923)
- 支持歌单封面接口
- 支持电台搜索接口
- [播放电台时允许在播放页使用基本功能](https://github.com/gitbobobo/StreamMusic/issues/982)
- [桌面端音量调整按钮移至控制栏](https://github.com/gitbobobo/StreamMusic/issues/998)
- [桌面端支持调整缓存位置](https://github.com/gitbobobo/StreamMusic/issues/1017)
- [subsonic 转码播放时使用预估时长代替实时时长](https://github.com/gitbobobo/StreamMusic/issues/983)，预估时长总会比实际时长多几秒
- 新增[音量淡入淡出开关](https://github.com/gitbobobo/StreamMusic/issues/1014)
- [设备没有摄像头时隐藏扫码入口](https://github.com/gitbobobo/StreamMusic/issues/988)
- [播放电台时隐藏播完停止的选项](https://github.com/gitbobobo/StreamMusic/issues/1031)
- [禁用每日推荐的排序功能](https://github.com/gitbobobo/StreamMusic/issues/1000)
- 修复 mac 状态栏歌词抖动问题
- 修复[电池优化多次提示的问题](https://github.com/gitbobobo/StreamMusic/issues/986)
- 修复[调整系统时区影响歌词时间轴的问题](https://github.com/gitbobobo/StreamMusic/issues/1028)
- 修复 [subsonic 专辑页面不显示专辑艺术家的问题](https://github.com/gitbobobo/StreamMusic/issues/1019)
- 修复 [Emby 和 Plex 无法同步 Last.fm 记录的问题](https://github.com/gitbobobo/StreamMusic/issues/894)

## V1.3.7（2025-04-28）

<Tabs groupId="operating-systems">
<TabItem value="android" label="Android">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} target="_blank" href="https://wwco.lanzouq.com/b00jecf93e">立即下载</Button>
</div>
</TabItem>

<TabItem value="win" label="Windows">

推荐直接通过微软应用商店安装。

<div class="mv-sm">
    <Button variant="contained" startIcon={<WindowIcon />} target="_blank" href="https://www.ilanzou.com/s/CWdZ0MgJ">立即下载</Button>
</div>

:::caution

若安装失败请查看[安装教程](/docs/guides/install)

:::
</TabItem>

<TabItem value="mac" label="macOS">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AppleIcon />} target="_blank" href="https://www.ilanzou.com/s/sXJZ0MF0">立即下载</Button>
</div>
</TabItem>
</Tabs>

更新内容：

- 新增[音乐漫游](/docs/guides/play#roaming)功能
- 新增[备用线路音质配置功能](https://github.com/gitbobobo/StreamMusic/issues/587)
- 新增歌词通知提前量配置
- 新增[软件内音量记忆功能](https://github.com/gitbobobo/StreamMusic/issues/931)
- [支持 Jellyfin 的私人歌单](https://github.com/gitbobobo/StreamMusic/issues/888)
- 支持平板模式和 TV 模式互相切换
- [支持播放 m3u8 电台](https://github.com/gitbobobo/StreamMusic/issues/883)（Windows 端不可用）
- 帮助页面增加 mpv 配置
- 优化[非同步歌词显示问题](https://github.com/gitbobobo/StreamMusic/issues/902)
- 优化[播放页非方形封面显示效果](https://github.com/gitbobobo/StreamMusic/issues/825)
- 优化自定义背景图片的性能表现
- [增加平板模式下歌词按钮底部边距](https://github.com/gitbobobo/StreamMusic/issues/890)
- [提升 Windows 端软件启动和退出速度](https://github.com/gitbobobo/StreamMusic/issues/916)
- 修复 navidrome 无法跳转歌手页的问题
- 修复[搜索结果无法全选加入歌单](https://github.com/gitbobobo/StreamMusic/issues/961)的问题

## V1.3.6（2025-03-20）

<Tabs groupId="operating-systems">
<TabItem value="android" label="Android">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} target="_blank" href="https://wwco.lanzouq.com/b00je8d17e">立即下载</Button>
</div>
</TabItem>

<TabItem value="win" label="Windows">
<div class="mv-sm">
    <Button variant="contained" startIcon={<WindowIcon />} target="_blank" href="https://www.ilanzou.com/s/zok0EbV7">立即下载</Button>
</div>

:::caution

若安装失败请查看[安装教程](/docs/guides/install)

:::
</TabItem>

<TabItem value="mac" label="macOS">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AppleIcon />} target="_blank" href="https://www.ilanzou.com/s/X4J0EbUt">立即下载</Button>
</div>
</TabItem>
</Tabs>


更新内容：

- [适配新版 navidrome 原生接口](https://github.com/gitbobobo/StreamMusic/issues/832)
- 支持编辑歌单信息
- 歌单导入导出支持 txt 格式（标题 - 歌手）
- 小于 3 首歌曲的专辑封面会显示歌曲数量
- 回放增益支持所有服务端
- 移除离线模式
- 应用内添加西班牙语的支持
- [Apple 平台播放长音频时媒体通知按钮改为快进快退](https://github.com/gitbobobo/StreamMusic/issues/865)
- [启动应用时自动播放会自动打开播放页](https://github.com/gitbobobo/StreamMusic/issues/878)
- [增强下一曲、上一曲按钮的视觉反馈](https://github.com/gitbobobo/StreamMusic/issues/837)
- 提升 Windows 端启动和退出应用时的体验
- 修复[删除空歌单文件时导致界面卡死的问题](https://github.com/gitbobobo/StreamMusic/issues/843)
- 修复无法删除最后一个歌单的问题
- 修复删除歌单中歌曲时会把所有相同歌曲都删掉的问题
- 修复 post 请求无法自动跟随重定向的问题
- 修复[没有可以播放的音乐时界面卡死的问题](https://github.com/gitbobobo/StreamMusic/issues/882)
- 修复 [mtw 相同标题的歌曲使用相同歌词的问题](https://github.com/gitbobobo/StreamMusic/issues/851)
- 修复[开启回放增益后音量不准确的问题](https://github.com/gitbobobo/StreamMusic/issues/562)

## V1.3.5（2025-01-18）

<Tabs groupId="operating-systems">
<TabItem value="android" label="Android">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} target="_blank" href="https://wwco.lanzouq.com/b00jdzrvmj">立即下载</Button>
</div>
</TabItem>

<TabItem value="win" label="Windows">
<div class="mv-sm">
    <Button variant="contained" startIcon={<WindowIcon />} target="_blank" href="https://www.ilanzou.com/s/Vs50I5BH">立即下载</Button>
</div>

:::caution

若安装失败请查看[安装教程](/docs/guides/install)

:::
</TabItem>

<TabItem value="mac" label="macOS">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AppleIcon />} target="_blank" href="https://www.ilanzou.com/s/d9D0I5O6">立即下载</Button>
</div>
</TabItem>
</Tabs>

更新内容:

- 支持 [Navidrome 的电台功能](https://github.com/gitbobobo/StreamMusic/issues/241)
- 提升多线路切换速度
- [歌词页添加粗体效果](https://github.com/gitbobobo/StreamMusic/issues/798)
- 登录时默认开启直连模式
- 下拉菜单适配桌面端 UI
- [桌面端添加屏幕常亮开关，避免一直点亮屏幕](https://github.com/gitbobobo/StreamMusic/issues/790)
- [Windows 支持同步 SMTC 播放进度](https://github.com/gitbobobo/StreamMusic/issues/722)
- 修复资料库详情页可能灰屏的问题
- 修复[媒体库模式获取不到歌单的问题](https://github.com/gitbobobo/StreamMusic/issues/794)
- 修复[下载歌曲被覆盖的问题](https://github.com/gitbobobo/StreamMusic/issues/781)
- 修复[切换到无歌词歌曲后，界面依旧显示上一句歌词的问题](https://github.com/gitbobobo/StreamMusic/issues/710)
- 修复[1970 年之前的专辑显示为未知年代的问题](https://github.com/gitbobobo/StreamMusic/issues/674)
- 修复[安卓桌面歌词拉大最大宽度后闪退的问题](https://github.com/gitbobobo/StreamMusic/issues/750)
- 修复[CarPlay 从歌手列表进入闪退的问题](https://github.com/gitbobobo/StreamMusic/issues/779)

## V1.3.4（2024-12-26）

:::caution

由于每日的下载量逐渐增大，CDN 流量成本已经有些难以承受。今后正式版本的**下载链接将通过网盘或 Github Release 发布**。

很抱歉给您造成的不便，不过请相信这都是暂时的，明年我将把上架安卓应用商店列为首要事项。

:::

<Tabs groupId="operating-systems">
<TabItem value="android" label="Android">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} target="_blank" href="https://wwco.lanzouq.com/b00jdws8cj">立即下载</Button>
    <span class="ml-md gray">密码: bd39</span>
</div>
</TabItem>

<TabItem value="win" label="Windows">
<div class="mv-sm">
    <Button variant="contained" startIcon={<WindowIcon />} target="_blank" href="https://www.ilanzou.com/s/dfMyb5zg">立即下载</Button>
    <span class="ml-md gray">MD5: 0312775fa5ab5e7d829bb95ef2f19791</span>
</div>

:::caution

若安装失败请查看[安装教程](/docs/guides/install)

:::
</TabItem>

<TabItem value="mac" label="macOS">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AppleIcon />} target="_blank" href="https://www.ilanzou.com/s/ZpwybpnX">立即下载</Button>
    <span class="ml-md gray">MD5: 8f413127e9ba4bc1eb398cdf10a18956</span>
</div>
</TabItem>
</Tabs>

更新内容:

- 👑 iOS 支持快捷指令
- 移动端首页支持显示用户头像（Emby,Jellyfin,Plex 可用）
- [windows 使用 NotoSansSC-Regular 作为默认字体](https://github.com/gitbobobo/StreamMusic/issues/760)
- 支持[m4a 格式转码播放](https://github.com/gitbobobo/StreamMusic/issues/611)
- 多线路增加蜂窝网络偏好
- 应用内添加安卓桌面歌词解锁按钮
- [增加上滑控制栏打开播放页的开关](https://github.com/gitbobobo/StreamMusic/issues/671)
- [桌面端图片资源均使用原图](https://github.com/gitbobobo/StreamMusic/issues/721)
- [CarPlay 艺术家列表支持按字母跳转](https://github.com/gitbobobo/StreamMusic/issues/698)
- 修复不打开 APP 无法使用 CarPlay 的问题
- 修复[创建歌单后，首页数据未刷新](https://github.com/gitbobobo/StreamMusic/issues/725)的问题
- 修复 [strm 文件无法播放的问题](https://github.com/gitbobobo/StreamMusic/issues/716)
- 修复[歌手详情专辑排序问题](https://github.com/gitbobobo/StreamMusic/issues/686)
- 修复 [Jellyfin 无法播放 ipv6 音乐链接的问题](https://github.com/gitbobobo/StreamMusic/issues/756)
- 修复[无法通过 Emby 的 Last.fm 插件上报播放记录的问题](https://github.com/gitbobobo/StreamMusic/issues/713)
- 修复 [Windows 端迷你窗口双击后会全屏显示的问题](https://github.com/gitbobobo/StreamMusic/issues/702)
- 修复[队列结尾无法下一曲到第一首的问题](https://github.com/gitbobobo/StreamMusic/issues/654)

## V1.3.3（2024-11-17）

<Tabs groupId="operating-systems">
<TabItem value="android" label="Android">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.3/app-arm64-v8a-release.apk">ARM64 版本</Button>
    <span class="ml-md gray">MD5: 010b0ccd625d3f7c872dab9da7502df6</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.3/app-armeabi-v7a-release.apk">ARMV7 版本</Button>
    <span class="ml-md gray">MD5: ae92e104f118c6b6f0a4256003cd8952</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.3/app-x86_64-release.apk">x86 版本</Button>
    <span class="ml-md gray">MD5: 0b44f215d577ecedef30b2e0f715a815</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.3/app-release.apk">通用版本（体积较大）</Button>
    <span class="ml-md gray">MD5: f6ff5c17704238315dfa5d82a26f126d</span>
</div>
</TabItem>

<TabItem value="win" label="Windows">
<div class="mv-sm">
    <Button variant="contained" startIcon={<WindowIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.3/stream_music_1.3.3.6.msix">立即下载</Button>
    <span class="ml-md gray">MD5: 2d474371df21c7d8cd1cd75e98f46363</span>
</div>

:::caution

若安装失败请查看[安装教程](/docs/guides/install)

:::
</TabItem>

<TabItem value="mac" label="macOS">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AppleIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.3/StreamMusic_1.3.3.dmg">立即下载</Button>
    <span class="ml-md gray">MD5: d2e1ca2f3b7ac1c2229499ef744565fb</span>
</div>
</TabItem>
</Tabs>

更新内容:

- 👑 桌面端支持迷你窗口
- 👑 iOS 14.2 及以上版本支持画中画歌词
- iOS 通知中心组件支持显示收藏按钮
- 桌面端新增[关闭窗口快捷键](https://github.com/gitbobobo/StreamMusic/issues/627)
- [桌面端支持全局热键](https://github.com/gitbobobo/StreamMusic/issues/363)，开关位于**帮助 - 快捷键**
- 多语言支持繁体中文
- 谷歌翻译接口可配置基础地址
- [自定义封面接口请求歌曲封面时会附加歌曲路径信息](https://github.com/gitbobobo/StreamMusic/issues/650)
- 调整安卓设置界面字体大小
- 媒体库模式在同步数据时可选择手动取消
- 支持[批量删除重复歌曲](https://github.com/gitbobobo/StreamMusic/issues/680)
- 优化[虚拟键盘自动隐藏逻辑](https://github.com/gitbobobo/StreamMusic/issues/639)
- 在不支持的服务端中隐藏文件夹和专辑艺术家的入口
- 安卓桌面歌词支持宽度调节
- 修复[安卓桌面歌词无法显示的问题](https://github.com/gitbobobo/StreamMusic/issues/615)
- 修复[逐字歌词解析问题](https://github.com/gitbobobo/StreamMusic/issues/605)
- 修复登录页面无法切换 TV 模式的问题
- 修复 Windows 端歌手详情页文字重叠的问题
- 修复[定时停止功能中，勾选播完当前歌曲后停止导致功能失效的问题](https://github.com/gitbobobo/StreamMusic/issues/618)
- 修复安卓耳机线控失效的问题
- 修复 DLNA 连接小爱音箱时无法更新播放状态的问题
- 修复切换资料库时首页部分数据未更新的问题

## V1.3.2（2024-10-04）

<Tabs groupId="operating-systems">
<TabItem value="android" label="Android">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.2/app-arm64-v8a-release.apk">ARM64 版本</Button>
    <span class="ml-md gray">MD5: 39d89dca63685ef98c440ca5efd2abeb</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.2/app-armeabi-v7a-release.apk">ARMV7 版本</Button>
    <span class="ml-md gray">MD5: 4fe07080fbe91f4f8b699a3da79c8aa4</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.2/app-x86_64-release.apk">x86 版本</Button>
    <span class="ml-md gray">MD5: 0fff06886b64b713337682793426639a</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.2/app-release.apk">通用版本（体积较大）</Button>
    <span class="ml-md gray">MD5: 99a4b99ed10d2d11e70318d925e30905</span>
</div>
</TabItem>

<TabItem value="win" label="Windows">
<div class="mv-sm">
    <Button variant="contained" startIcon={<WindowIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.2/stream_music_1.3.2.6.msix">立即下载</Button>
    <span class="ml-md gray">MD5: 81cf96d4ee3c6b122eab1456e6a673e3</span>
</div>

:::caution

若安装失败请查看[安装教程](/docs/guides/install)

:::
</TabItem>

<TabItem value="mac" label="macOS">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AppleIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.2/StreamMusic_1.3.2.dmg">立即下载</Button>
    <span class="ml-md gray">MD5: bbad7b8ad5030553dae4357b59a9bab0</span>
</div>
</TabItem>
</Tabs>

更新内容：

- 移动端添加桌面小组件（播放控制与实时歌词）
- 为设置界面项目添加图标(主题中开启)，并适应各平台风格
- 播放界面适应亮色风格
- 支持在应用内切换语言
- 优化歌手详情页在移动端横屏状态的表现
- [单曲循环时允许按下一曲切歌](https://github.com/gitbobobo/StreamMusic/issues/487)
- [AudioStation 支持按音轨号排序](https://github.com/gitbobobo/StreamMusic/issues/525)，新增按音轨号排序方式
- [稍微增加横屏状态下播放页封面的尺寸](https://github.com/gitbobobo/StreamMusic/issues/448)
- [重复歌曲数量大于 9 时显示为 9+](https://github.com/gitbobobo/StreamMusic/issues/589)
- 播放页的歌词选项添加「生成翻译」功能
- [优化屏幕常亮触发逻辑](https://github.com/gitbobobo/StreamMusic/issues/600)
- 媒体库模式下，[同年发行的专辑按照专辑名排序](https://github.com/gitbobobo/StreamMusic/issues/476)
- [媒体库模式使用实时搜索](https://github.com/gitbobobo/StreamMusic/issues/599)
- 修复 [Windows 端无法搜索到 DLNA 设备的问题](https://github.com/gitbobobo/StreamMusic/issues/578)
- 修复无法播放 DSF 格式的问题 #388 #548
- 优化歌曲缓存逻辑，现已重新支持不转码播放 ogg 格式
- 修复 [VIVO 系手机不显示通知组件的问题](https://github.com/gitbobobo/StreamMusic/issues/394)
- 修复安卓通知栏播放按钮无法点击的问题
- 修复 [Jellyfin 封面不显示](https://github.com/gitbobobo/StreamMusic/issues/535)的问题
- 修复[切换播放模式后界面未更新](https://github.com/gitbobobo/StreamMusic/issues/537)的问题
- 修复 Subsonic 直连模式获取不到歌手的歌曲列表的问题
- 修复 [AudioStation 全部播放随机范围过小](https://github.com/gitbobobo/StreamMusic/issues/526)的问题
- 修复[播放已下载歌曲无法自动切歌的问题](https://github.com/gitbobobo/StreamMusic/issues/557)
- 修复[歌单内包含重复歌曲导致无法在启动时恢复播放列表的问题](https://github.com/gitbobobo/StreamMusic/issues/538)
- 修复 [windows 端无法切换歌单的问题](https://github.com/gitbobobo/StreamMusic/issues/576)

## V1.3.1（2024-09-02）

<Tabs groupId="operating-systems">
<TabItem value="android" label="Android">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.1/app-arm64-v8a-release.apk">ARM64 版本</Button>
    <span class="ml-md gray">MD5: dd95dadfc5e0da5390a56a4c2333b529</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.1/app-armeabi-v7a-release.apk">ARMV7 版本</Button>
    <span class="ml-md gray">MD5: c6cc33ba5efa185d3daea8f62bdf399a</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.1/app-x86_64-release.apk">x86 版本</Button>
    <span class="ml-md gray">MD5: be12b8d86a1d9867c6b2b6cfbddcee47</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.1/app-release.apk">通用版本（体积较大）</Button>
    <span class="ml-md gray">MD5: 4e8d8000211401a7f1aa5f36a63ef0c7</span>
</div>
</TabItem>

<TabItem value="win" label="Windows">
<div class="mv-sm">
    <Button variant="contained" startIcon={<WindowIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.1/stream_music_1.3.1.5.msix">立即下载</Button>
    <span class="ml-md gray">MD5: 9eb42a5d0d3730034ec76030dee86bb9</span>
</div>

:::caution

若安装失败请查看[安装教程](/docs/guides/install)

:::
</TabItem>

<TabItem value="mac" label="macOS">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AppleIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.1/StreamMusic_1.3.1.dmg">立即下载</Button>
    <span class="ml-md gray">MD5: 156a5e98e00c9e0287f36169be4cbf38</span>
</div>

:::caution

当前版本修复了与最新版 Mac 系统的兼容问题，安装前需要先在访达 - 应用程序按 `Command + Delete` 删除之前安装的版本，否则会同时存在两个音流。

:::
</TabItem>
</Tabs>

更新内容：

- [DLNA 功能修复](https://github.com/gitbobobo/StreamMusic/issues/254)
- [Windows 新增任务栏快捷操作与播放进度显示](https://github.com/gitbobobo/StreamMusic/issues/220)
- 新增专辑艺术家列表（仅 Emby 和 Jellyfin 有效，其他服务端等同于歌手列表）
- 支持多艺术家跳转(此前默认跳转第一个)
- 支持[配置代理地址](https://github.com/gitbobobo/StreamMusic/issues/447)
- 去掉实时搜索逻辑（可能导致搜索时间过长），需按回车键触发搜索
- 手机端的首页显示资料库别名
- 调整纯色主题配色
- 对话框样式改为各个平台的原生样式，后续将逐步替换其他组件
- 支持[上报播放中的状态](https://github.com/gitbobobo/StreamMusic/issues/437)
- [歌曲详情显示缓存位置](https://github.com/gitbobobo/StreamMusic/issues/151)
- Emby/Jellyfin 增加全部分区的选项
- 封面显示逻辑调整回原来的（歌曲展示歌曲封面，专辑展示专辑封面）
- [修改歌曲列表默认封面](https://github.com/gitbobobo/StreamMusic/issues/468)
- 优化重定向歌曲资源的处理逻辑
- 调整歌词偏移后，按对勾会调用歌词确认接口
- [调整歌词与翻译的间距](https://github.com/gitbobobo/StreamMusic/issues/474)
- 同步数据的 IP 地址现可识别多网卡的 IP 地址
- [恢复自定义 API 保存按钮](https://github.com/gitbobobo/StreamMusic/issues/458)
- [媒体库模式文件夹模糊搜索](https://github.com/gitbobobo/StreamMusic/issues/481)不再对大小写敏感
- [提升歌手详情页按钮可见性](https://github.com/gitbobobo/StreamMusic/issues/477)
- 兼容 [macOS Beta 3](https://github.com/gitbobobo/StreamMusic/issues/414)
- 修复无法导入歌单的问题
- 修复自定义歌单顺序无法保存的问题
- 修复首页批量歌单歌曲时只能下载第一首的问题
- 兼容 [Jellyfin 10.8](https://github.com/gitbobobo/StreamMusic/issues/429)
- 修复 Plex 在 CarPlay 中点击歌曲列表后闪退的问题
- 修复 [Jellyfin 不显示封面的问题](https://github.com/gitbobobo/StreamMusic/issues/435)
- 修复无法删除已下载的歌曲的问题
- 修复媒体库模式下最近与最常播放不显示的问题
- 修复[直连模式下群晖无法按歌手筛选专辑和歌曲的问题](https://github.com/gitbobobo/StreamMusic/issues/433)
- 修复添加 BaseUrl 后无法播放的问题 [#438](https://github.com/gitbobobo/StreamMusic/issues/438) [#396](https://github.com/gitbobobo/StreamMusic/issues/396)
- 修复[无法播放文件夹下歌曲的问题](https://github.com/gitbobobo/StreamMusic/issues/473)
- 修复[媒体库模式下群晖无法按添加时间倒序](https://github.com/gitbobobo/StreamMusic/issues/459)的问题
- 修复[支付宝订单号恢复页面按钮不可用的问题](https://github.com/gitbobobo/StreamMusic/issues/453)
- 修复[低版本安卓无法恢复购买的问题](https://github.com/gitbobobo/StreamMusic/issues/469)
- 修复 [TV 版第二次打开时可能卡在启动页](https://github.com/gitbobobo/StreamMusic/issues/446)的问题
- 修复桌面端搜索到多个歌词时无法滚动选择的问题（添加底部指示器）
- 修复[随机播放歌单内歌曲时随机范围过小](https://github.com/gitbobobo/StreamMusic/issues/530)的问题
- 修复修改系统时区后歌词不会自动滚动的问题
- 修复[播放高码率文件可能出现电流声](https://github.com/gitbobobo/StreamMusic/issues/518)的问题

## V1.3.0（2024-07-25）

:::success 早鸟优惠<sup>2</sup>

为庆祝音流达成适配安卓 TV 的里程碑，特开启第二波早鸟优惠，活动时间为 2024-07-26 至 2024-08-08。

在此期间音流会员价格将降低 10 元，您可以 38 元的特惠价购入音流终身会员。

活动结束后，音流终身会员价格将调整至 58 元。

:::

<Tabs groupId="operating-systems">
<TabItem value="android" label="Android">
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.0/app-arm64-v8a-release.apk">ARM64 版本</Button>
    <span class="ml-md gray">MD5: 1cddbc720c19dde02d9d50d9a2106c35</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.0/app-armeabi-v7a-release.apk">ARMV7 版本</Button>
    <span class="ml-md gray">MD5: 445eaba3783884ddb4207e99947ebd52</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.0/app-x86_64-release.apk">x86 版本</Button>
    <span class="ml-md gray">MD5: b9bb45b1be24ca2efb9a1fcbcdc8b668</span>
</div>
<div class="mv-sm">
    <Button variant="contained" startIcon={<AndroidIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.0/app-release.apk">通用版本（体积较大）</Button>
    <span class="ml-md gray">MD5: 6ecf08468ec68879f50d78dc14dfd628</span>
</div>
</TabItem>

<TabItem value="win" label="Windows">
<div class="mv-sm">
    <Button variant="contained" startIcon={<WindowIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.0/stream_music_1.3.0.5.msix">立即下载</Button>
    <span class="ml-md gray">MD5: 94a7f1c000e033c59fbed040590bb94c</span>
</div>
</TabItem>

<TabItem value="mac" label="macOS">

:::caution

Mac OS 请暂时不要升级至 Beta 3 版本，会导致音流无法使用。

:::

<div class="mv-sm">
    <Button variant="contained" startIcon={<AppleIcon />} href="https://oss2.aqzscn.cn/stream-music/versions/1.3.0/音流v1.3.0.dmg">立即下载</Button>
    <span class="ml-md gray">MD5: c622937c89b16df5eb510b129e1dd3c8</span>
</div>
</TabItem>
</Tabs>

更新内容：

- [适配安卓 TV](https://github.com/gitbobobo/StreamMusic/issues/23)，建议手机上下载安装包后，通过 [localsend](https://github.com/localsend/localsend) 发送给 TV 端，以便后续更新。
- 新增扫码同步数据的功能（若无法识别请返回重进换一个二维码）
- 支持[多服务器切换](https://github.com/gitbobobo/StreamMusic/issues/35)，支持分区选择
- 支持按流派筛选歌曲/专辑/歌手
- 支持自定义歌单排序
- 提升线路切换速度（主线路连接失败后，优先使用最先连接成功的线路）
- 增加标记歌曲为已播放的功能
- 升级歌曲定位功能
- [按评分筛选增加没有评分的选项](https://github.com/gitbobobo/StreamMusic/issues/362)
- 支持[主线路编辑](https://github.com/gitbobobo/StreamMusic/issues/327)
- 依次同步歌曲、专辑和歌手数据以解决[服务器并发请求过多无法正常获取响应](https://github.com/gitbobobo/StreamMusic/issues/365)的问题
- 长音频播放页的上一曲下一曲按钮改为快进快退
- [播放时忽略未完整缓存的歌曲](https://github.com/gitbobobo/StreamMusic/issues/316)
- [切歌之后如果没有图片，显示默认 Logo](https://github.com/gitbobobo/StreamMusic/issues/305)
- 调整 Windows 返回按钮位置
- [Audio Station 支持选择转码比特率](https://github.com/gitbobobo/StreamMusic/issues/286)
- 支持 [Jellyfin 的歌词接口](https://github.com/gitbobobo/StreamMusic/issues/289)
- [Emby/Jellyfin 不校验密码是否填写](https://github.com/gitbobobo/StreamMusic/issues/377)
- [Navidrome 占位图片视为无图片](https://github.com/gitbobobo/StreamMusic/issues/355)
- 修复媒体库模式下歌手页面无法搜索歌手的问题
- 修复[媒体库模式评分和收藏操作界面不更新](https://github.com/gitbobobo/StreamMusic/issues/348)的问题
- 修复自动下载会重复下载歌曲的问题
- 修复[自定义歌词接口切换歌词失效](https://github.com/gitbobobo/StreamMusic/issues/392)
- 修复[重新打开 app 后无法记忆上次播放位置的问题](https://github.com/gitbobobo/StreamMusic/issues/236)
- 修复一些卡在加载中提示的情况
- 修复单曲循环只上报了一次播放记录的问题
- 修复专辑页面和歌单页面的排序问题，[#301](https://github.com/gitbobobo/StreamMusic/issues/301), [#303](https://github.com/gitbobobo/StreamMusic/issues/303)
- 修复 ogg 格式只有第一次能播放的问题（缓存的 ogg 格式数据有问题，临时处理方式：对所有 ogg 格式转码后播放）
- 修复[搜索结果页歌曲无法播放的问题](https://github.com/gitbobobo/StreamMusic/issues/297)
- 修复[流派详情页未筛选数据的问题](https://github.com/gitbobobo/StreamMusic/issues/422)
- 修复 Emby 可能不显示歌词的问题
- 修复 [Emby 最近播放和最常播放顺序颠倒](https://github.com/gitbobobo/StreamMusic/issues/376) 的问题
- 修复 [Audio Station 登录过期后不显示图片，无法播放的问题](https://github.com/gitbobobo/StreamMusic/issues/321)
- 修复[媒体库模式无法识别 MTW 的歌手简介的问题](https://github.com/gitbobobo/StreamMusic/issues/311)
- 修复群晖或 Plex 自动获取的 IP 会重复添加的问题
- [Android] 修复[关闭系统省电模式后，从任务管理器杀死应用，音乐仍在播放的问题](https://github.com/gitbobobo/StreamMusic/issues/239)

文档更新：

使用说明部分有较多更新，建议完整阅读。
