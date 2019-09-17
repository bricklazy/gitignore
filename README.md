git 更新忽略文件步骤：
1. 将准备好的忽略文件（.gitignore）放至项目根目录。
2. 清空缓存
    ``` bash
    git rm -r --cached .
    ```
3. 重新添加 
    ``` bash
    git add .
    ```
4. 提交更新信息
    ``` bash
    git commit -m "update .gitignore"
    ```
5. 同步至远端
    ``` bash
    git push
    ```
