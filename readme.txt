数字小游戏
 
  1.首先v-model,数据的双向绑定
	根据你文本框输入的值变化而变化. 
  2.@click绑定一个click事件,其中@是v-on的缩写.
	当然绑定事件可以带参数例如@click='time(item)'. 
  3.v-for="(index, item) in list"
  循环数组,index为数组的角标,item为数组中的值. 

演示地址：https://arrowjava.github.io/vue-demo1/demo1.html