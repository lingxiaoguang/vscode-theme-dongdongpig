
# Dongdong pig - VS Code theme
![dongdong](icon.png)

[源码链接](https://github.com/lingxiaoguang/dongdongpig)

东东是一头可爱的小猪，让它每天陪着你写代码吧~

他会一直在你编辑器左侧哦~

![dongdongpigtheme](theme.png)

## Installation
1. 安装一个插件[custom-css-and-js-loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)（支持加载css和js)并且启用
![eable-custom-css-and-js](./eable-custom-css-and-js.png)

2. 保存[`dongdongpig.css`](https://raw.githubusercontent.com/lingxiaoguang/dongdongpig/master/dongdongpig.css)到本地， 然后打开settings.json配置如下

    Mac：

    ```
    {
      "vscode_custom_css.policy": true,
      "vscode_custom_css.imports": [
        "file:///Users/{文件位置}/dongdongpig.css"
        ]
    }
    ```

    Windows:

    ```
    {
      "vscode_custom_css.policy": true,
      "vscode_custom_css.imports": [
        "file://C:/{文件位置}/dongdongpig.css"
        ]
    }
    ```

3. 重启就可以生效啦~

## Thanks

感谢一直陪伴着我的东东~


