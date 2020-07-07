1. A B C D
2. D

patchVnode执行过程？
目的：对比新旧两个结点, 更新差异。

执行过程：
首先prepatch钩子函数，update钩子函数，结点对比完成之后，会触发postpatch钩子函数。

