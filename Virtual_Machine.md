The Java HotSpot Virtual Machine is a core component of the Java SE platform. It implements the Java Virtual Machine Specification, and is delivered as a shared library in the Java Runtime Environment. As the Java bytecode execution engine, it provides Java runtime facilities, such as thread and object synchronization, on a variety of operating systems and architectures. It includes dynamic compilers that adaptively compile Java bytecodes into optimized machine instructions and efficiently manages the Java heap using garbage collectors, optimized for both low pause time and throughput. It provides data and information to profiling, monitoring and debugging tools and applications.

Java HotSpot 虚拟机是Java SE 平台的核心组件，它实现了Java虚拟机规范，在Java运行环境作为一个共享库被提供。作为Java字节码执行引擎，它在各种操作系统和架构，提供Java运行时能力，例如线程和对象同步。它包含动态编译器，可以自适应编译Java字节码为优化的机器指令，使用垃圾收集器高效的管理Java堆。它为分析，监控和调试工具和应用程序提供数据和信息。



HotSpot is an "ergonomic" JVM. Based upon the platform configuration, it will select a compiler, Java heap configuration, and garbage collector that produce good to excellent performance for most applications. Under special circumstances, however, specific tuning may be required to get the best possible performance. The resources collected here will help the reader understand and tune the Java HotSpot Virtual Machine.
HotSpot 是一个符合人体工程学的的JVM。基于平台配置。它将选择一个编译器，Java堆配置，和垃圾收集器，为大多数应用程序产生出色的性能。但是，在一些特别情况下，可能需要特定调整才能获取最佳性能。这里收集的资源将帮助读者理解和调整Java Hotspot虚拟机。
