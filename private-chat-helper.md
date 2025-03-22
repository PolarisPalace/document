## 联系管理员注册账号

1. 打开 `https://space.bilibili.com`
2. 打开`开发者工具`（按 `F12` 或 `Ctrl+Shift+I`）
3. 点击`开发者工具`顶部的选项卡切换到 `Console`（`控制台`），如果没有，请点击 `+` 添加
4. 在控制台中输入以下命令并回车执行
    ```
    const input = document.createElement('input'); input.value = document.getElementsByClassName('b-avatar__layer__res')[0].children[0].children[1].src.split('@')[0]; document.body.appendChild(input); input.select(); document.execCommand('copy'); document.body.removeChild(input);
    ```
5. 如果控制台不能粘贴内容，请按照其提示输入 `允许粘贴` 或 `allow pasting`
6. 剪贴板中的内容即为你的头像链接
7. 将你的头像链接、账号、你所在的部门发送至 `Gugle2308`（微信），`2308465862`（QQ）
8. 所有账号的初始密码均为 `abc123`，请在管理员注册后立即登录并修改密码

## 联系管理员添加已登录的B站账号

1. 打开`开发者工具`（按 `F12` 或 `Ctrl+Shift+I`）
2. 点击`开发者工具`顶部的选项卡切换到 `Application`（`应用程序`），如果没有，请点击 `+` 添加
3. 在左侧菜单中选择 `Cookies`，然后选择 `https://www.bilibili.com`
4. 你可以看到所有存储的 `Cookie`，选择 `DedeUserID`， `SESSDATA`， `bili_jct`，复制下方的 `Cookie Value` 并发送至
   `Gugle2308`（微信），`2308465862`（QQ）
5. 请使用以下格式发送
    ```
    DedeUserID=xxxxxxxxxx
    SESSDATA=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
    bili_jct=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
    ```
6. 注意该内容为隐私信息，请勿在公开场合发送。
