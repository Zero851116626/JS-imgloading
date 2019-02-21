# JS-imgloading
瀑布流加载图片
原生javascript编写的瀑布流加载图片

### 使用方法
新建一个类，传入以下参数
n：number
  表示列数
str：dom节点
  内部通过document.querySelector()实现
  选择一个容器来存放这些图片
 width：number
  单位是“px”，写入时不加单位
 interval：number
  每张图片之间的间隔
  默认是10px
  写入时不带单位
  
### 接口功能
.addImg
  通过这个方法导入单张图片，
  如果想一次性导入多张图片，最好是将这多张图片组成一个数组，然后遍历数组，通过addImg添加图片
