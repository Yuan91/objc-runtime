# objc-runtime
基于**objc runtime 756.2**的可调试版本runtime

# 使用方法

* 编译`objc` target 生成 `libobjc.A.dylib`

* 编译`debug-objc` target ，如果报错可能只因为要配置为Mac Developer，选择一个整数就好

* 然后就可以在`main.m`放肆的调试、打断点窥探`objc`的底层了
