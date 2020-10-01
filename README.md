# curriculum-vitae 
#### 使用 HTML / CSS / JS 写的个人前端简历；
****
#### 已完成移动端适配：
****
- 引用淘宝网移动端适配样式，
```
<meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,user-scalable=no,viewport-fit=cover"> 
```
- 使用媒体查询，  
```
<style media="print">  
	body {  
	 margin: 0;  
	}  		
</style>  
```
- CSS中A4纸边界限定，
```
article {  
	width: 21cm;  
	min-height: 29.7cm;  
	background: white;  
	margin: 0 auto;  
	overflow: auto;  
	padding: 1em;  
	}  
```
#### ECharts 图表的使用：  
****
- 下载 echarts.min.js 文件  
- 网页中引用相关文件（有顺序，echarts.min.js 在 main.js 之前）
```
<script src="JS/echarts.min.js"></script>    
<script src="JS/main.js"></script>  
```
- 自己在 main.js 中，参考 ECharts 官网查看应用实例，进行改造。  
