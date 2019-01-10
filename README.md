# aboutPython
# this repository is created for taking notes about the features of Python

        '''
        1. for i in range()作用
        '''
        range()是一个函数， for i in range () 就是给i赋值： 
        比如 for i in range （1，3）： 
        就是把1,2依次赋值给i 
        range () 函数的使用是这样的: 
        range（3）即：从1到3，不包含3，即0,1,2 
        range(1,3) 即：从1到3，不包含3，即1,2 
        range（1,3,2）即：1,2。第三个数字2是代表步长。如果不设置，就是默认步长为1

        For i in range(100) 
        则读取normMat[i,:]样本的编号为：0-99，共100个
        
        ...
        2. python[::-1]和[-1]用法
        ...
        [::-1] 顺序相反操作 
        [-1] 读取倒数第一个元素 
        [3::-1] 从下标为3（从0开始）的元素开始翻转读取 
        同样适用于字符串 
        eg：
        input：
            a=[1,2,3,4,5]
            b=a[::-1]
        output：
           [5, 4, 3, 2, 1]
        input：
            b=a[-1]
        output：
            5
        input：
            b=a[3::-1]
        output：
            [4, 3, 2, 1]

