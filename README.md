# static-server 极简静态资源服务器

## 测试

```
const StaticServer = require('../src/index');

const staticServer = new StaticServer({
	port: 9527,
  rot: '/public',
});

staticServer.start();

// staticServer.close();
```
