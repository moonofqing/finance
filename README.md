# finance
尝试springcloud
尚融合宝创建过程第一小节总结
1、springboot项目创建
2、先配置与mysql数据库连接
![image](https://user-images.githubusercontent.com/93534344/143876835-792bbf5f-1bee-4435-a129-d2c69cd886d8.png)
创建实体类对象作为映射读取数据保存
![image](https://user-images.githubusercontent.com/93534344/143877095-dfe837dc-26b6-4654-9868-023ad3f41aee.png)
3、创建mapper映射接口，继承basemapper接口类，该类为mybatis封装的增删改查等通用接口
![image](https://user-images.githubusercontent.com/93534344/143877962-9207787f-cd79-446e-afa4-ae83cceb9b14.png)
4、测试 
![image](https://user-images.githubusercontent.com/93534344/143878231-d8d54bf6-b00b-4cd4-b3d4-b8ab9c6d826a.png)
5、成功读取出和输出数据库中User表中数据
6、 以上都是springboot中对于DAO层的合并集成
