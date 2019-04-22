# 第五节 BOM对象
## history对象
    属性
        history.length
    方法
        后退back()
        前进forward()
        刷新go(0)
        前进go(1)
        后退go(-1)
## document对象
    属性
        write( ）
        子主题 2
        body
    方法
## location对象
    属性
        herf
            包含了url全部
        protocol
            协议
        host
            包含域名，端口号
        hostname
            url域名
        port
            端口号
        pathname
            中间路径，虚拟路径和文件
        search
            参数
        hash
            锚点
    方法
## window对象(核心)
    属性
    方法
        setInterval(function(){},1000)
            时间函数
            每隔1000ms执行上面的函数
                js计时不准，因为遵循单线程异步机制
            单线程：代码执行只能顺序执行，不能再开启一个，效率比较低
            异步机制：看当前是否有占用，能不能同时两个进程
                clearInterval()
        setTimeout（)
            倒计时
                倒计时几秒钟以后执行
