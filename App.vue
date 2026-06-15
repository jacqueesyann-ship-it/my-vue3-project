<script>
export default {
  onLaunch: function () {
    console.log('App Launch')
  },
  onShow: function () {
    console.log('App Show')
  },
  onHide: function () {
    console.log('App Hide')
  },
}
</script>

<style>
/*每个页面公共css */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body,
html,
#app {
  width: 100%;
  height: 100%;
  background-color: #ffffff;
}

/* 全局字体设置 */
body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu',
    'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

/* 输入框全局样式 */
input {
  font-size: 16px;
}

/* 按钮全局样式 */
button {
  font-family: inherit;
  cursor: pointer;
  border: none;
}

/* 链接样式 */
a {
  color: #27ae60;
  text-decoration: none;
}

a:active {
  color: #229954;
}
</style>

