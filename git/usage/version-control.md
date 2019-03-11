# 版本控制

我们知道 `git` 是分布式版本控制系统,所以称被控制对象是版本本身没错,但是从`git` 命令中发现,并没有版本这个名词,有的只是`commit`,所以前几节我一直称其为**提交**.

为了避免后续教程引发歧义,特意说明,无论是**版本**也好,**提交**也罢,都是中文翻译而已,不必太过较真,直接原汁原味称`commit`也可以啊!

假设你已掌握暂存区的相关概念,简单来说,暂存区就是更改文件的缓存集合,等待一次性全部提交到版本库,正因如此,方便我们批量操作相关性文件,打包提交到版本库,这正是暂存区的独特魅力.

我们反复在说 `git` 是分布式版本控制系统,分布式的概念已经粗略讲过多次了,下面我们讲一下版本控制,谈谈 `git` 的版本控制和其他系统的版本控制有什么不同,为什么 `git` 这么优秀,如此流行?
