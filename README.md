# cominvi-clone

仿照 [CoMinVi](https://www.cominvi.com.mx/)（墨西哥矿业承包公司官网）开发的前端静态项目，仅用于前端学习与技术研究。

## 本地预览

站点使用 ES Module 动态加载，请通过本地 HTTP 服务预览（直接双击 index.html 部分功能会受限）：

```bash
python -m http.server 8777
```

浏览器打开 <http://127.0.0.1:8777/>

## 内容

- 英文 / 西班牙文双语言页面树：首页、about-us、our-services、technology、safety、blog、contact 等 26 个页面
- 全部静态资源：图片（avif/webp/svg/png）、字体（woff2）、背景视频、600 帧滚动驱动动画序列
- 交互实现：GSAP + Lenis 平滑滚动引擎、canvas 图像序列、3D 效果、地图交互

## 声明

原站的文案、图片、字体、商标及代码版权归原作者所有。本仓库仅供学习交流使用，请勿用于任何商业用途；如有侵权请联系删除。
