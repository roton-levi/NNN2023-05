# levi-c
c-algorithm-master (t5w0rd/c-algorithm-master)( /tlang 1 逗号表达式是优先级最低的右值表达式，右值是可以进行求值的表达式  2 但某些带都号语法的表达式里，可使用的优先级最低的右值表达式是赋值表达式  3 逻辑或表达式是二元表达式中优先级最低的表达式，用于赋值表达式的基础构成  4 语法表达式中，多项式项优先级一定高于最左端被声明的表达式  下面表达式中，A可能由两种情况构成：  单独由一个B构成，B的优先级要高于A  由一个A和一个B构成，可以理解为A是B的列表，B是A的列表项  A : B | A B alloc_object()函数可能会触发GC，由于crb_create_xxx()函数内部会调用alloc_object()函数，所以这类可能触发GC的函数在连续出现的时候，前一个crb_create_xxx()函数不可以使用中间变量去接收返回值，否则容易其后面的GC释放掉))


//20230514 Fix Bugs Of ecd rsa sha1 sha2  ed22519