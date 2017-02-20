# Zaiqiuchang admin web app demo

[Zaiqiuchang(在球场)](https://www.zaiqiuchang.com) is a mobile app developed using react native, both iOS and Android are supported. This open source project is the lite version of the admin web app, which developed using react, redux and bootstrap. This project can be used as a react web app starter kit.

### Screenshots

<img src="https://zqc.cdn.zaiqiuchang.com/screenshot/admin/admin-dev.png?x-oss-process=style/w-720" />

### Packages

|Package|Description|
|-------|-----------|
|[react](https://github.com/facebook/react)|Build ui component.|
|[redux](http://redux.js.org/)|Manage ui state.|
|[react-router](https://github.com/ReactTraining/react-router)|Page route.|
|[axios](https://github.com/mzabriskie/axios)|Http request.|
|[react-icons](https://github.com/gorangajic/react-icons)|Using material design and font awesome icon as react component.|
|[reactstrap](https://github.com/reactstrap/reactstrap)|Using bootstrap 4 components in react.|
|[bootstrap](https://v4-alpha.getbootstrap.com/)|Layout and css framework.|
|[karma](https://github.com/karma-runner/karma)|Run test.|
|[webpack](https://github.com/webpack/webpack)|Package app, transform es6 javascript and sass css source code.|

### How to run

```
> git clone git@github.com:jaggerwang/zqc-admin-demo.git && cd zqc-admin-demo
> npm i # you may need a proxy to improve download speed, if failed, remove node_modules directory and retry.
> npm run dev
...
webpack: Compiled successfully.
```

Open url 'http://localhost:3000' to view the app. When code modified, the app will auto reload the change.

### How to package

```
> cd zqc-admin-demo
> npm run deploy:prod
  ...
  app:bin:compile No errors or warnings encountered. +44ms
  app:bin:compile Copying static assets to dist folder. +3ms
  app:bin:compile Compilation completed successfully. +34ms
```

The packaged app is saved in dist directory. To deploy, you only need to copy dist to your web server's root path.

### Other resources

* [在球场官网](https://www.zaiqiuchang.com)
