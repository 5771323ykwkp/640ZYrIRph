# 高校学生饮食推荐系统

## 前言

随着健康饮食意识的不断提升，针对高校学生的饮食习惯和营养需求，我们开发了一套高校学生饮食推荐系统。本系统致力于为高校学生提供合理的饮食建议，改善其饮食习惯，促进健康生活。以下是本项目的详细介绍。

## 内容介绍

本系统基于Java开发，采用Spring Boot框架，前端使用JS、Vue和css3技术。通过对学生饮食习惯的大数据分析，推荐适合学生的菜品和食谱。系统主要包括以下功能：用户注册登录、个人信息管理、饮食推荐、食谱查询、健康数据分析等。此外，系统还提供了丰富的互动环节，如评论、点赞、分享等，让学生在享受美食的同时，也能参与到饮食健康的交流中。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于饮食推荐功能的相关代码：

```java
@Service
public class DietRecommendService {

    @Autowired
    private DietRecommendMapper dietRecommendMapper;

    public List<Dish> recommendDishes(String userId) {
        // 根据用户ID查询用户口味偏好
        User user = dietRecommendMapper.getUserById(userId);
        // 查询推荐菜品
        List<Dish> dishes = dietRecommendMapper.recommendDishes(user.getTaste());
        return dishes;
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

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/325305/13/4917/145247/689ee067Fca956f11/637689b90592be24.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/318283/1/24260/36568/689ee045F043d4c39/6c8faf5b060764e8.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/319315/14/25537/90542/689ee046F164c8f1e/e245bb949750fe69.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/325647/13/4694/81041/689ee046F017dcc28/88464ed4cc5355a6.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/294455/17/27323/22369/689ee047F1f8c7d83/88c90a6bed49350a.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/320824/19/24790/41620/689ee047Ffdf3e1ad/036182dde7c5cf76.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/313955/6/26775/29831/689ee048F2d6db191/29264efa27437288.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/322126/17/9084/22256/689ee048F62f7b230/95c24bc3f6585f90.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/311334/21/26830/31597/689ee049Fd95c0fa2/ac03c88f40991787.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/308762/33/26656/38970/689ee04aF26b2f1c5/89de49689190a541.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
