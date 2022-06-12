# developer-plus 周刊（第 5 期）：iconfont 回来了

记录每周值得分享的内容，周一发布。

本周刊开源（GitHub: [developer-plus/weekly](https://github.com/developer-plus/weekly)），欢迎提交 [issue](https://github.com/developer-plus/weekly/issues/new/choose)，投稿或推荐科技内容。

## 本周话题：iconfont 回来了

[iconfont](https://www.iconfont.cn) 平台经过紧急升级维护，目前重要功能已优先恢复，其他功能也会尽快完成升级维护，并逐步恢复。

<img src="https://hongbusi.oss-cn-hangzhou.aliyuncs.com/weekly/5-0.png">

## 开源

1、[支持远程办公的中国公司](https://github.com/LinuxSuRen/remote-jobs-in-china) (@Hongbusi 投稿)

相比于集中式办公，远程办公（remote）在国内（中国）依然是一种不是很普遍的工作方式。远程办公，不用拘束于具体的地理位置（城市，甚至国家），这对于热衷于追求自由的人而言，无疑充满了诱惑。尤其是，对于已经厌倦了在北、上、广工作时需要较长通勤时间（大于1小时）的人，远程办公“可能”是一种解脱。

2、[中国程序员容易发音错误的单词](https://github.com/shimohq/chinese-programmer-wrong-pronunciation) (@TickHeart 投稿)

## 软件

1、[uTools 新一代效率工具平台](https://www.u.tools) (@Soya-xy 投稿)

多平台支持 Mac\Win\Linux。各种插件提高开发、办公效率。

<img src="https://hongbusi.oss-cn-hangzhou.aliyuncs.com/weekly/5-1.png">

2、[Karabiner-Elements](https://karabiner-elements.pqrs.org) (@Hongbusi 投稿)

Karabiner-Elements 是一个功能强大的实用程序，用于在 macOS Sierra 或更高版本上进行键盘自定义。

<img src="https://hongbusi.oss-cn-hangzhou.aliyuncs.com/weekly/5-2.png">

## 网站

1、[字节图标库](https://iconpark.oceanengine.com) (@Soya-xy 投稿)

一款字节的图标、插画库。

<img src="https://hongbusi.oss-cn-hangzhou.aliyuncs.com/weekly/5-3.png">

## 日常踩坑

1、[模块的默认导出具有或正在使用专用名称 “Props”](https://github.com/developer-plus/weekly/issues/31) (@Hongbusi 投稿)

**问题背景：**

``` vue
<script setup lang="ts">
interface Props {
  title: string
}

defineProps<Props>() // Error：模块的默认导出具有或正在使用专用名称 “Props”。
</script>
```

**解决方案：**

移除 `composite:true` 在 tsconfig.json 中，警告消失。详见：https://github.com/johnsoncodehk/volar/issues/1232

**问题原因：**

使用 `pnpm create vite` 初始化项目之后，嫌两个配置文件看起来过于多余，于是手动合并了 `tsconfig.json` 和 `tsconfig.node.json`。

Vite 中关于修改 tsconfig.json 的讨论： 

- https://github.com/vitejs/vite/issues/6311
- https://github.com/vitejs/vite/pull/6324

**相关文档：**

https://www.typescriptlang.org/docs/handbook/project-references.html

## 订阅

微信搜索 **「Developer plus」** 或者扫描二维码，即可订阅。

<img src='https://hongbusi.oss-cn-hangzhou.aliyuncs.com/qrcode.jpg' width='222' />

developer-plus made with 💗. (完)
