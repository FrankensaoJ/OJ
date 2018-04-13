##  题意

求一棵树的最大深度（层数），并求出有多少个最深的叶结点

##  样例解释

*   第一行

    | 输入 | 说明 |
    | --- | --- |
    |9 | 第2行数字的个数 |
    | 1.80 | 初始价格 |
    | 1.00 | 每经过一个中间商，价格就会上涨，1.00 表示涨价 1.00% |

*   第二行

    | 输入数字 | 序号 |
    | --- | --- |
    | 1 | 0 |
    | 5 | 1 |
    | 4 | 2 |
    | 4 | 3 |
    | -1 | 4 |
    | 4 | 5 |
    | 5 | 6 |
    | 3 | 7 |
    | 6 | 8 |

    `序号`相当于子节点，`输入数字`相当于父节点

    其中由于`-1`所表示的`root`，其序号是4，也就是说，4号节点是`root supplier`

    由第二行可以得到一个树形关系，
    
    ```
    4
    |---2
    |---3
    |   |---7
    |
    |---5
        |---1
        |   |---0
        |
        |---6
            |---8
    ```