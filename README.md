# querymorewords
一个简单的爬虫程序，用于查询单词。</br>
写这个程序的动机是要背考纲的单词，高考考纲上是没有单词释义的，就想写一个程序一次性把单词释义查出来。</br>
从同目录下的sample.txt文件按行读取单词并从有道词典爬取单词释义输出。</br>
可用PowerShell等直接读到查询结果。</br>
sample.txt中已经放了A开头的考纲单词用于测试。</br>
2017.6.30：新增加了将结果输出到output.txt。</br>
2017.7.13：新增加了exe打包。共享给别人时发现很多人并没有安装python环境，所以将这个程序打包成exe。</br>
2017.9.2：优化单词未被收录时无法继续的问题。单词未被收录时会输出一个“未收录”，而不是停止程序。
2017.9.2：新增输出到csv的功能。
2017.11.24：csv程序多项修改。csv程序独立放置在csv文件夹中；修复csv程序重复输出的bug；删除csv程序同时输出txt的功能，两种文件格式需用两个程序输出。
2017.12.22：修复编码错误（由于minute等单词的释义中含有音标，输出时原本会出现编码错误）。