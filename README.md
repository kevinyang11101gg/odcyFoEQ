# 前言

药品配送系统在现代社会中起着至关重要的作用，它能够确保药品的安全、快捷、准确地送达患者手中。基于SSM（Spring、SpringMVC、MyBatis）的药品配送系统，利用先进的技术手段，优化了药品配送流程，提高了配送效率。以下是本项目的详细介绍。

## 内容介绍

本项目基于SSM框架，实现了一套完整的药品配送系统。系统主要包括以下几个模块：用户模块、订单模块、配送模块、药品管理模块等。通过这些模块，可以实现对药品配送全过程的实时监控和管理。此外，系统还提供了完善的权限控制功能，确保数据安全。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12/14/16

## 核心代码

以下是本项目中的一段核心代码，展示了如何使用MyBatis实现药品信息的查询：

```java
// Mapper接口
public interface DrugMapper {
    @Select("SELECT * FROM drug WHERE id = #{id}")
    Drug selectDrugById(int id);
}

// 药品实体类
public class Drug {
    private int id;
    private String name;
    private String specification;
    // 省略其他属性和方法
}

// Service层调用
@Service
public class DrugService {
    @Autowired
    private DrugMapper drugMapper;

    public Drug getDrugById(int id) {
        return drugMapper.selectDrugById(id);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/344001/6/1910/213846/68c1a755F92083a79/d7730b3998ab44a1.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/331288/8/11760/30862/68c1a72cF567c3f55/54b99089fb26de29.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326816/30/18633/158111/68c1a72dF23c1f99e/aa5582b98b3a2136.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328582/16/18477/16569/68c1a72dF64d394a0/199653190438d034.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/349332/17/1934/31463/68c1a72dFad7eb6a0/54c9de39d01a85b2.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/340264/33/9296/32238/68c1a72eF2c4eab10/fcedddf7f7dd1d34.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/338623/32/8132/54252/68c1a72eF6acfa90f/42f8e0fa0ffd899c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/347487/16/1889/33317/68c1a72eF177e8769/967713fc37b98515.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/328684/31/18379/30226/68c1a72fF43f94e18/6f1b1022b9f25e00.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/344564/31/1910/23792/68c1a72fF91fbff2e/2672863a3451724f.jpg)

