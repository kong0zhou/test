这是一个前端上传文件的组件,包含对应的后端代码
    里面还有一个没有优化
    例如:假设后端没有能把内存里的数据拷贝到磁盘,会出现错误,但前端不清楚
        前端有一个angular的bug,一次请求会变成两次

前端用material的ui库,使用时记得导入这个库,以及包含一个主题