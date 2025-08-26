## [redragon-erp](https://gitee.com/redragon/redragon-erp) has a shiro deserialization vulnerability

Shiro key hardcoded：

![image-20250826231353545](./images/image-20250826231353545.png)

Screenshot of successful exploitation (no output)：

![image-20250826231746714](./images/image-20250826231746714.png)

![image-20250826231839753](./images/image-20250826231839753.png)

This problem occurs when redragon-erp is started in SpringBoot mode.

