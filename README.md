
## 可滑动切换的小程序tab-view组件
### 参考
原始代码见 https://github.com/zhongjie-chen/wx-scrollable-tab-view </br>
将原仓库的tab-view封装成小程序组件，方便模块化开发
</br>

### 使用方法

1. 导入：在需要使用此组件的页面配置中引入
2. 使用示例：

``` html
<ScrollTabView tabs="{{['头条', '体育', '财经', '娱乐']}}">
    <view slot="头条">1</view>
    <view slot="体育">2</view>
    <view slot="财经">3</view>
    <view slot="娱乐">4</view>
  </ScrollTabView>
```
注意tabs数组应与view中的slot名字对应