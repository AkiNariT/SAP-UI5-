UI5学习。
记录常用class，function等。  

<h2> 初期配置 </h2> 
1.下载node.js  

2.编辑器选则Vscode或者Eclipses。  
早期学习JAVA时常使用Eclipes，且CDSview也在其中操作，但本回学习使用VScode。

3.npm install --global @ui5/cli  
将上述输入到VScode的终端行可下载ui5。但可能会触发PowerShell禁止执行.ps1脚本，导致失败。  
也可以CMD执行。同样可以下载ui5。下载完可以尝试下ui5 --version。返回版本号，意味成功。

4.建立文件夹。最好在纯英文路径下。我的命名为UI5APP。  
回到VScode，打开建立的文件夹。查看终端行，可以确认是否在正确路径。  
在终端行输入npm init --yes 会生成package.json。  
如有失败，可能是PowerShell导致的。  
那就输入npm.cmd init --yes

5.在UI5APP下建立新的文件夹webapp。  
输入ui5 init会生成ui5.yaml。切记路径是UI5APP下。

6.在webapp下创建manifest.json  
输入 { "sap.app":{ "id":"sap.ui.demo.walkthrough" } }

7.在UI5APP下ui5 use SAPUI5@latest 。  
这会确认ui5的版本。会反映在ui5.yaml上

8.在webapp下生成一个index.html
这里就是我们熟悉的HTML的标签操作了。

9.回到UI5 APP,输入UI5 server就可以打开网页查看我们的html页面了



<h2> 初级教学参照路径： </h2>
[UI5 Walkthrough JavaScript 教程](./docs/03_Get-Started/walkthrough-tutorial-javascript-3da5f4b.md)
