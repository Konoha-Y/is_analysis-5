<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：getTest  [返回](../README.md)
用例： [查看实验](../用例/查看实验.md)

- 功能：
    学生查看发布的实验。
    
- 权限：
    学生 
    
- API请求地址： 
    接口基本地址/v1/api/getTest

- 请求方式 ：
    POST

- 请求实例：

        {
            "term-year":1,
            "course_name":"java"
             "test_id":"实验一",
             "title":"java",
            "substance: "××××××××××××××",
            "date": "2018.6.2",
            "teacher_name":"黄老师" ,
        }
        
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |term-year|学年|
  |course_name|java|
  |test_id|实验ID|
  |title|实验标题| 
  |substance|实验内容|
  |data|实验发布时间|
  |teacher_name|黄老师|
  
- 返回实例：

        {         
            "status": true,
            "info": null,    

        }
 
- 返回参数说明： 
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|


