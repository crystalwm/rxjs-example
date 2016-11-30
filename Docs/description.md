
工作的步骤：
* Step1: 初始化DOM事件流

        1：为plus的click事件创建一个可观察对象plusObservable
        2:  为minus的click事件创建一个可观察对象minusObservable

* Step2: 映射源Observable的value

        1: 将plusObservable的值映射为一个新的Observable值为1
        2: 将minusObservable的值映射为一个先的Observable值为-1

* Step3: 归并多个Observable成一个新的对象

        将plusObservable和minusObservable归并成一个Observable
* Step4：迭代多个Observable的值，并申城一个新的Observable
       
        将plusObservale的值和minusObservable的值累加
* Step5: 为Observable订阅事件处理函数
