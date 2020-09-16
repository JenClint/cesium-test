# cesium-test

##cesium
  加载谷歌地球影像
  var url = "http://mt1.google.cn/vt/lyrs=s&hl=zh-CN&x={x}&y={y}&z={z}&s=Gali"
  var google = new Cesium.UrlTemplateImageryProvider({url:url})
  
  var viewer =new Cesium.Viewer('cesiumContainer',{
            imageryProvider:google,
        });
  
  
##控件
  baseLayerPicker:false,    //图层选择控件
  animation:false,          //左下角仪表
  timeline:false,           //时间线控件
  fullscrenbutton:false,    //右下角全屏按钮
  geocoder:false,           //地名查找控件
  imageryProvider:google,   //地图加载控件
  
