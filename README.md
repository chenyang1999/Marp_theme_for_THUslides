# Marp_theme_for_THUslides
使用 Marp 制作清华大学组会 Slides模板(可以换自己学校的背景图片)

因为懒,不想用 PPT 做组会的 Slides,所以马哥做了一个 Marp 的模板直接套平时 Markdown 的笔记,就能出 Slides.

用法：看马哥写的Slides.md，结合源代码读生成的PDF，然后再自己试着做一个就会了。

好处:

1. Markdown语法,复制黏贴笔记就行了
2. 打公式方便
3. 排版比 Latex 模板更方便

BUG:
1. 导出 PDF 的时候记得先关掉预览

2. 实在导不出,用 terminal 命令导出 html,再用浏览器转 PDF(其实直接用 html 也行...)

导出 html :`marp Slides.md`
导出 PDF :`marp Slides.md --pdf`