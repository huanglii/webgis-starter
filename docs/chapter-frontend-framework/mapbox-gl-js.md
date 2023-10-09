# Mapbox GL JS

[Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/api/) 是一个 JavaScript 库，基于 [vector tiles](https://docs.mapbox.com/help/glossary/vector-tiles/) 和 [Mapbox styles](https://docs.mapbox.com/mapbox-gl-js/style-spec/)，使用 `WebGL` 渲染交互式地图。Mapbox GL JS 是 Mapbox GL 生态系统之一，其中还包括 [Mapbox Mobile](https://www.mapbox.com/mobile/)，它是一个用 C++ 编写的兼容桌面和移动平台的渲染引擎。

```js
import mapboxgl from 'mapbox-gl'
import 'mapbox-gl/dist/mapbox-gl.css'

// 初始化地图
const map = new mapboxgl.Map({
  accessToken = '{YOUR MAPBOX ACCESS TOKEN}'
  container: 'map', // 地图容器 id
  style: 'mapbox://styles/mapbox/streets-v11', // 样式
  center: [104.294538, 35.860092], // 地图初始中心点
  zoom: 1.2, // 地图初始缩放级别
})

// 添加导航控件
const nav = new mapboxgl.NavigationControl({
  visualizePitch: true
})
map.addControl(nav)
```
