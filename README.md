# subconverter-heroku-koyeb
subconverter自动部署到heroku
subconverter自动部署到heroku

# 具体操作请见博客   https://blog.imkcp.xyz/subconverter/

## 部署到heroku
subconverter-heroku：https://github.com/BlueHtml/subconverter-heroku

步骤如下：

forksubconverter-heroku项目
添加Secret：HEROKU_API_KEY和HEROKU_EMAIL
修改heroku.yml里的heroku_app_name的值
点击Actions->点击heroku->点击Run workflow
部署后访问/version，如果出现subconverter v版本号 backend说明部署成功。

## 部署到koyeb

点一下这个图标,然后全部默认就行

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=docker&name=subconver&ports=8080;http;/&image=jth445600/subconver)
