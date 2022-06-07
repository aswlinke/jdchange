# subconverter-heroku
subconverter自动部署到heroku

部署到heroku
subconverter-heroku：https://github.com/aswlinke/jdchange

步骤如下：

forksubconverter-heroku项目
添加Secret：HEROKU_API_KEY和HEROKU_EMAIL
修改heroku.yml里的heroku_app_name的值
点击Actions->点击heroku->点击Run workflow
部署后访问/version，如果出现subconverter v版本号 backend说明部署成功。
