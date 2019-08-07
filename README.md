# test-postcss-preset-env

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

###  重点配置：

 importFrom:一定不能没有。需要你手动指定你定义的 CSS路径。

```json
"postcss": {
    "plugins": {
      "postcss-preset-env": {
        "stage": 1,
        "importFrom": "src/assets/common.pcss"
      }
    }
  }
```

