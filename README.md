### PEA-SHARING

本项目是一个使用Golang编写的简单Web服务，提供了文件上传和下载的功能。用户可以通过该服务上传文件到服务器的uploads目录，并且可以通过下载链接下载已上传的文件。

#### 功能
* 文件上传：用户可以通过Web界面上传文件到服务器的`uploads`目录。
* 文件下载：用户可以通过下载链接下载服务器`uploads`目录中的文件。

#### 使用场景
该项目适用于需要在Web应用中实现文件上传和下载功能的场景，例如：
* 网站用户上传头像或其他文件。
* 管理员上传和分享文件。

#### 使用方法
1. 启动服务：在项目根目录下执行`go run main.go`命令启动服务。
2. 访问网页：在浏览器中访问`http://localhost:8080`，即可进入文件上传页面。
3. 上传文件：在网页中选择文件并上传到服务器。
4. 下载文件：通过下载链接下载已上传的文件。

#### 技术栈
* Golang：使用Golang编写后端服务。
* Gin框架：使用Gin框架构建Web应用。
* BOOTSTRAP框架：使用BOOTSTRAP构建前端界面。

欢迎使用和贡献！