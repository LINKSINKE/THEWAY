

.nojekyllin./docs来防止GitHub Pages忽略以下划线开头的文件。
```shell
└── docs/
    ├── _sidebar.md
    ├── index.md
    ├── getting-started.md
    └── running-services.md


```

:scream:


1、ico图标无法显示的问题


```html
<link rel="icon" href="_media/favicon.ico">
```


/
|--/_assets:
|     存放外部引用的资源文件
|--/_mynote:
|     存放需要导入的md文件
|--/.nojekyll:
|     默认的文件
|--/
|     
|--/
|     
|--/
|     
|--/
|     
|--/index.html
|     配置文件
|--/README.md
|     初始文件
|--/readme.txt
|     说明文件
|--/
|     
- _navbar.md
导航
- _sidebar.md
- CNAME
域名配置
- _coverpage.md：封面配置
- index.html：作为入口文件
- README.md：作为主页
- .nojekyll：防止GitHub Pages忽略以下划线开头的文件
- start.cmd：windows启动脚本
- .nojekyll
