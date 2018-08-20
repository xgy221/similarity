# similarity
计算评论数据的相似性

- tmp文件夹下存放着one_day_review.py,jieba_one_day.py以及similarity.py
one_day_review.py:爬取所需的三十条评论\<br>
jieba_one_day.py：对评论数据进行预处理操作——分词、去停止词\<br>
similarity.py：计算每组评论数据的评级相似性\<br>

- data文件夹下存放着stop_words.txt文件

- paper_needed文件夹下存放着保存下来的评论数据

- 对于代码中显示红色下划线的import语句，在已经安装Python并配置好环境的前提下，在终端使用：pip install 包名即可