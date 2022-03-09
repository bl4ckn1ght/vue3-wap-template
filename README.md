# Vue 3 + Vite + postcss + pnpm + px2vw

这是一个基于vue3+vite+postcss+pnmp的移动端适配模板，拥有以下特点：
* px to vw （比px2rem更好的适配方案）[浏览器兼容性](https://caniuse.com/?search=vw)
* 1px border on retina screen（使用svg来实现1px边框）
* vite（更好更快的构建工具）
* pnpm(更好更快的依赖管理工具，支持workspace等新特性)

## 项目依赖
|名称|版本|文档|描述|
|-|-|-|-|
|vite|^2.8.0|https://vitejs.cn/config/|下一代前端开发与构建工具|
|@vitejs/plugin-vue|^2.2.0|https://github.com/vitejs/vite/tree/main/||packages/plugin-vue|||
|postcss|^8.4.8|https://github.com/postcss/postcss/blob/main/docs/README-cn.md|是一个用 JavaScript 工具和插件转换 CSS 代码的工具|
|postcss-write-svg|^3.0.1|https://github.com/csstools/postcss-write-svg||
|@bl4ckn1ght/postcss-px2vw|0.0.1|https://github.com/bl4ckn1ght/postcss-px-to-viewport|postcss插件 px to vw|
|autoprefixer|^10.4.2|https://github.com/postcss/autoprefixer|PostCSS plugin to parse CSS and add vendor prefixes to CSS rules using values from Can I Use. It is recommended by Google and used in Twitter and Alibaba.|
|postcss-import|^14.0.2|https://github.com/postcss/postcss-import#readme|PostCSS plugin to transform @import rules by inlining content.|
|postcss-nested|^5.0.6|https://github.com/postcss/postcss-nested|PostCSS plugin to unwrap nested rules like how Sass does it.|