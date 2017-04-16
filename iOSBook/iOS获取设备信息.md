<p align="center" >
<img src="https://raw.githubusercontent.com/zhangkeqingc/bookmark/master/Sources/鸡年.png" alt="AFNetworking" title="AFNetworking">
</p>


# iOS开发笔记-获取设备的信息
 

```bash
NSLog(@"globallyUniqueString=%@",[[NSProcessInfo processInfo] globallyUniqueString]);//全球唯一标识  
NSLog(@"uniqueIdentifie=%@",[UIDevice currentDevice].uniqueIdentifier);//唯一的标识 可用于区分设备  
NSLog(@"name=%@",[UIDevice currentDevice].name);//设备的名称  李四的 iPad、王五的 iPad .。。  
NSLog(@"systemName=%@",[UIDevice currentDevice].systemName);//系统的名称  iPhone OS  
NSLog(@"systemVersion=%@",[UIDevice currentDevice].systemVersion);//设备系统的版本号  5.1.1、6.0  
NSLog(@"model=%@",[UIDevice currentDevice].model);//设备的型号   iPad、iphone、ipod touch。。。  
NSLog(@"localizedModel=%@",[UIDevice currentDevice].localizedModel);//本地化的模型  iPad  
NSLog(@"batteryLevel=%lf",[UIDevice currentDevice].batteryLevel);//电池电量 

```


