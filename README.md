# 思源《高等数学》样板项目
下载页： https://github.com/tritium333/advancedmath_siyuan/releases 

现已更新至第一章第三节。

本项目具有如下特色：
1. 知识点之间的引用。比如书中凡是出现“连续”的地方，我都链接到“连续”这一定义所在块，方便温故知新。
2. 每个定理、定义都制成闪卡。
3. 每个定理、定义都链接到 pdf 教材的原文位置。

可随意用于教学、学习、科研、思源的宣传推广、教程制作等用途。

![图片](https://github.com/tritium333/advancedmath_siyuan/assets/158309317/d2028e02-1559-4ab0-931e-c3c8882c7f68)
![图片](https://github.com/tritium333/advancedmath_siyuan/assets/158309317/1325bf57-e5c0-4a8a-97df-cd09c378b4a5)
![图片](https://github.com/tritium333/advancedmath_siyuan/assets/158309317/41317917-76d0-4193-9b8f-737842a7f4e9)
![图片](https://github.com/tritium333/advancedmath_siyuan/assets/158309317/9b99c6c8-84f3-4362-8821-52e20e440b34)
![图片](https://github.com/tritium333/advancedmath_siyuan/assets/158309317/ff39c5cc-bb64-405e-bfd4-014b6e88cde6)
![图片](https://github.com/tritium333/advancedmath_siyuan/assets/158309317/c084ff6d-2abd-4df1-aedc-6c0740b7c8a2)
![20240201_182641](https://github.com/tritium333/advancedmath_siyuan/assets/158309317/a52d731a-17d7-4bd3-976d-ccd8e3a91e30)
![图片](https://github.com/tritium333/advancedmath_siyuan/assets/158309317/c3528b6a-16d2-41a3-a059-9b8372568981)

为保证手机端的体验，请添加如下css代码片段：
```css
/* 全局隐藏列表小圆点 */
/* ↓ 文字左移 ↓ */
.protyle-wysiwyg [data-node-id][data-subtype="u"].li>[data-node-id] {
    margin-left: 0 !important;
}
/* ↓ 隐藏小圆点，但小圆点原位置仍然可点击 ↓ */
.protyle-wysiwyg [data-node-id][data-subtype="u"].li>.protyle-action>svg>use:not(:hover) {
    opacity:0;  /* 如果希望此处不可点击， 自行替换为 display:none; */
}
/* ↓ 竖线稍微左移，更美观 ↓*/
.protyle-wysiwyg [data-node-id][data-subtype="u"].li:before {
    left:11px;  /* 如果希望此处不显示竖线， 自行替换为 display:none; */
}
```
思源默认的引用颜色不是很好看，建议通过以下css代码片段修改：
```css
/* 默认浅色主题引用颜色 */
:root:has(#themeDefaultStyle[href *="daylight"]) .protyle-wysiwyg [data-node-id] span[data-type~=block-ref]:not(.av__celltext), .protyle-wysiwyg [data-node-id] span[data-type~=file-annotation-ref] {
    color: #7958b8; 
}

/* 默认暗黑主题引用颜色 */
:root:has(#themeDefaultStyle[href *="midnight"]) .protyle-wysiwyg [data-node-id] span[data-type~=block-ref]:not(.av__celltext), .protyle-wysiwyg [data-node-id] span[data-type~=file-annotation-ref] {
    color: #ceb4ff; 
}

/* 去掉反链面板中引用的背景色 */
.protyle-wysiwyg [data-node-id] .def--mark {
    background-color: transparent;
}
```

鸣谢：

- [思源笔记](https://b3log.org/siyuan/)
- [SimpleTex - 好用的公式识别神器！](https://simpletex.cn/)
- [quicker](https://getquicker.net/Sharedaction?code=2605ff05-b84f-4da6-107c-08db6a78bc4a)
