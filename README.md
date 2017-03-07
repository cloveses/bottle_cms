# bottle_cms

环境要求：
1.python3
2.bottle + sqlalchemy

后台数据库：
sqlite3
由于使用了ORM，后台可以轻松切换到其它关系型数据库。

基本实现了内容管理所需要的用户注册、登录与管理、内容分类管理、内容管理与审核等功能，便于扩展。

其它：
集成CKEDITOR作为HTML富文本编辑功能，方便内容发布。