# php依赖注入容器

使用方法：
    
    //获得容器
    $app = new Boomdawn\Container();
    
    //向容器中绑定组件
    $app->bind('组件标识', '类名称|类实例');
    
    //单例绑定
    $app->bindSingle('组件标识', '类名称|类实例');
    
    //从容器中取出对象
    $app->make('标识名称',[参数]);
