# HK_stocks
传入url太快了，考虑分成两部分完成：1.先存到数据库中或其他容器中（数据结构不行）
 2. 再从数据库中逐个调取进行爬取   3. 中间过渡的数据库是用内存型（redis) 还是一般存储型的？
4.数据量小，爬取，传入，再解析影响不大，但是分布式爬取大量数据，就必须要切割开来，才能各司其职，有效处理各自的工作！
5.容器是必备，分布式必备，代理池也是必备
