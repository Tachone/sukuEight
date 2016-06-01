Muduo is a multithreaded C++ network library based on
the reactor pattern.
It runs on Linux with kernel version >= 2.6.28.

高性能数独和八数码问题求解服务器，使用muduo网络库构建<br>
数独使用Dancing Links算法求解，<br>
输入格式为a:000000.00000(81个数字，a:标记为可选内容)<br>
八数码使用A*算法+康托展开优化完成，<br>
输入格式为12436x857,空格用x代替，默认求解的目的结果为12345678x，返回结果为操作的方向字符串最短集合<br>

    依赖于muduo网络库和boost库，使用cmake编译
    核心代码位于examples中。
    博客 http://blog.csdn.net/nk_test/article/details/51525015 中有更加详细的说明。

![](https://github.com/Tachone/sukuEight/blob/master/%E9%80%89%E5%8C%BA_003.png) 

最后，欢迎前端的同学一起来完善这个项目，使得交互更加人性化。



