# vscode-
first
一、实验目的
1.能熟练掌握Vue基本指令
2.能熟练掌握Vue插值和相关数据绑定方法
二、实验内容
1.课时
2学时2.预备知识
(1）插值绑定(2）实例创建(3）常用指令3.内容
使用Vue 的常用指令实现小米商城首页“手机”模块的数据展示效果。
1.编写列表数据对象。
const phoneList = [
{id:'100081',img:'images/phone1.png',title:'Redmi K50电竞版',des:'全线拉满的冷血旗舰',price:'3299元起'},
2.使用HTML和 CSS编写页面元素和样式。
参考地址: https://www.mi.com/
3．使用v-for指令遍历phoneList，展示手机数据。
<li class="xxx"v-for="xx in xxx" :key="xxx">...</li>4．使用gitee 的 pages服务部署以上实验的页面。
