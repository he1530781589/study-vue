## 一个HelloVue入门vue
**html**
```html
    <div id="app">
        {{message}}
    </div>
```
**js**
```javascript
    var app = new Vue({
        el: '#app',
        data: {
            message: 'Hello Vue!'
        }
    })
```