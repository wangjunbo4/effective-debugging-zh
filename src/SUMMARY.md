# 目录

[译者注](./translator_preface.md)
[引言](./introduction.md)
- [第一章 调试符号和调试器](./chapter_1.md)
    - [调试符号](chapter_1/01-01debug_symbols.md)
    - [调试符号概览](chapter_1/01-02debug_symbol_overview.md)
    - [DWARF格式](chapter_1/01-03dwarf_format.md)
    - [不一致的数据类型](chapter_1/01-04inconsistent_data_type.md)
    - [调试器的内在](chapter_1/01-05debugger_internal.md)
    - [技巧和注意事项](chapter_1/01-06tips_and_caveats.md)
    - [特殊的调试符号](chapter_1/01-07ad_hoc_debug_symbol.md)
    - [断点和监测点](chapter_1/01-08breakpoints_and_watchpoints.md)
    - [改变运行和副作用](chapter_1/01-09alter_execution_and_side_effect.md)
    - [自动化符号匹配](chapter_1/01-10automate_symbol_matching.md)
    - [事后的分析](chapter_1/01-11post_mortem_analysis.md)
    - [内存保护](chapter_1/01-12memory_protection.md)
    - [断点不工作](chapter_1/01-13breakpoints_doesnt_work.md)
    - [总结](chapter_1/01-14summary.md)
- [第二章 堆数据结构](./chapter_2.md)
    - [理解内存管理器](./chapter_2/02-01understand_memory_manager.md)
    - [Ptmalloc](./chapter_2/02-02ptmalloc.md)
    - [Tcmalloc](./chapter_2/02-03tcmalloc.md)
    - [多个堆](./chapter_2/02-04multiple_heaps.md)
    - [利用堆元数据](./chapter_2/02-05leverage_heap_metadata.md)
    - [总结](./chapter_2/02-06summary.md)
- [第三章 内存损坏](./chapter_3.md)
    - [内存是怎么损坏的](./chapter_3/03-01how_is_memory_corrupted.md)
    - [调试内存损坏](./chapter_3/03-02debug_memory_corruption.md)
    - [案例学习](./chapter_3/03-03cases_study.md)
- [第四章 C/C++对象布局](./chapter_4.md)
    - [对齐](./chapter_4/04-01alignment_and_endian.md)
    - [大小端](./chapter_4/04-02endian.md)
    - [C++对象布局](./chapter_4/04-03object_layout.md)
    - [搜索引用树](./chapter_4/04-04search_references_tree.md)
- [第五章 优化后的二进制](./chapter_5.md)
    - [调试版本和发行版本的区别](./chapter_5/05-01diff_between_debug_and_release.md)
    - [调试优化代码的挑战](./chapter_5/05-02challenges_debugging_optimized_binary.md)
    - [汇编代码介绍](./chapter_5/05-03assembly_intro.md)
- [第六章 进程镜像](./chapter_6.md)
- [第七章 多线程问题](./chapter_7.md)
- [第八章 更多调试进程](./chapter_8.md)
- [第九章A Python拓展gdb](./chapter_9.md)
    - [美化输出](./chapter_9/09-01pretty_printer.md)
    - [将重复的工作变成一个命令](./chapter_9/09-02dry.md)
    - [编写你自己的美化器](./chapter_9/09-03write_your_owner_pretty_printer.md)

- [第十章A 使用地址消毒工具](./chapter_10.md)
- [附录A 拓展调试能力](./appendix_A.md)
- [附录B 调试混合语言](./appendix_B.md)
