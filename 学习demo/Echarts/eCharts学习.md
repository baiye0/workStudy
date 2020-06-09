# eCharts

## 1.配置图表的3步

```javascript
//1.基于给定ID的dom,初始化实例
var myChart = echarts.init(document.getElementById('main'))
//2.指定图表的配置项和数据
var option = {
			title:{
				text:'Echartsdemo1'
			},
			tooltip:{},
			legend:{
				data:['销量']
			},
			xAxis:{},
			yAxis:{},
			series:[{
				name:'销量',
				type:'bar',
				data:[5,20,36,10,10,20]
			}]
		};
//3.使用刚配置的数据项显示图表
myChart.setOption(option)
```

![img](https://echarts.apache.org/zh/documents/asset/img/basic-concepts-overview/components.jpg)

