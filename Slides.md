---
marp: true
theme: gaia
paginate: true
footer: 'Designed by Marcus 2020-12-01'
style: | 
  section footer{color:black;font-size: 20px;} 


---
<style scoped>
section h1 {text-align: center;font-size: 80px;color:black;}
section {
  background-image:url('./fm.png');
  background-size:cover
}
footer{color:black;font-size: 20px;} 
</style>
<!-- _class: lead gaia -->

# Marp for THU slides

---
<style >

section{
  background-image:url('./bg.png');
  background-size:cover;
  position: absolute;
  }
section h1 {font-size:40px;color:black;margin-top:px;}
section h2 {font-size:30px;color:black;margin-top:px;}
section p {font-size: 25px;color:black;}
section table {text-align: center;font-size: 32px;color:black;}
section a {font-size: 25px;color:black;}
li {font-size: 30px;text-align: left;}

img {
    margin-left: auto; 
    margin-right:auto; 
    display:block;
    margin:0 auto;
    width:25cm;
    }
</style>

<style scoped>
section h1 {font-size:60px;color:black;margin-top:px;}
li {font-size: 50px;text-align: left;}
</style>

# 总览
1. 如何使用
2. 首页修改
3. 背景修改
4. 图片格式
5. 左右排布
6. CSS 说明

---
# 如何使用 Marp 制作组会 Slides
1. 下载 VS code
2. 在插件中心安装Marp for VS Code
3. 新建一个 md 文件,复制 1~51 行 CSS 或者从该模板中直接新建.
4. 点击 1 可以实时显示 Slides,点击 2 选择 export 可以导出 PDF. 
![w:10cm](https://cy-1256894686.cos.ap-beijing.myqcloud.com/20201129171243.png)

---
# 首页修改
我预设了适合展示的标题大小,当然如果是需要修改适合投影的字体大小可在源代码中第 12 行修改`h1的font-size`.

改变`background-image:url('./fm.png');`可以修改首页背景图片.

```css
<style scoped>
section h1 {text-align: center;font-size: 80px;color:black;}
section {
  background-image:url('./fm.png');
  background-size:cover
}
footer{color:black;font-size: 20px;} 
</style>
```

---
# 背景修改
修改模板源代码 27~31 行`background-image:url('./bg.png');`中背景图片即可.
```css
section{
  background-image:url('./bg.png');
  background-size:cover;
  position: absolute;
  }
```

---
# 字体修改
全局格式修改在源代码 31~35 行
`h1`一级大标题
`h2`二级大标题
`p`正文字体
`table`表格字体,居中
`li`列表字体,居左
```css
section h1 {font-size:40px;color:black;margin-top:px;}
section h2 {font-size:30px;color:black;margin-top:px;}
section p {font-size: 25px;color:black;}
section table {text-align: center;font-size: 32px;color:black;}
section a {font-size: 25px;color:black;}
li {font-size: 30px;text-align: left;}
```

---
# 图片格式
默认居中,临时在某一slides中修改可以
```css
<style scoped>
img {
    margin-left: auto; margin-right:auto; 
    display:block;margin:0 auto;width:25cm;
    }
</style>
或者:
![w:2cm h:2cm](fm.png)
```
![w:2cm h:2cm](fm.png)

---
# 左右排布
```
![bg left:40% w:5cm h:5cm](fm.png)
```
![bg left:40% w:5cm h:5cm](fm.png)

---
# 左右排布
```
![bg right:40% w:5cm h:5cm](fm.png)
```
![bg right:40% w:5cm h:5cm](fm.png)

---
# CSS 说明
```
https://www.w3school.com.cn/css/css_image_gallery.asp

https://marpit.marp.app/theme-css
```

# 更多细节
```
https://marpit.marp.app/usage
```

# 更多Markdown 语法
```
https://www.markdown.xyz/basic-syntax/
```

---
<style scoped>
section h1 {text-align: center;font-size: 100px;color:black;}
section {
  background-image:url('./fm.png');
  background-size:cover
}
footer{color:black;font-size: 20px;} 
</style>
<!-- _class: lead gaia -->

# 谢谢朋友们