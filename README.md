# Zhihu-Spider

目录结构：

知乎

-- frame  框架

&nbsp; &nbsp; SpyderFrame.py 通用爬虫框架

-- tools  工具

&nbsp; &nbsp; KeyWordsSearch.py 关键词搜索

-- utils

&nbsp; &nbsp; question.py 知乎回答爬虫，爬某个提问下面全部的回答以及回答的详细信息, 存入MongoDB.知乎.questions

&nbsp; &nbsp; wiki_box.py 知乎百科数据，知乎某些question被收录进知乎百科里，这里仅保留百科词条，question具体信息有专门处理的文件（utils/question.py）

&nbsp; &nbsp; user.py 知乎用户信息爬虫