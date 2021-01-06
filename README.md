## 作业仓库

### python pytest 测试实战 1

#### 课后作业

1. 补全计算器（加法 除法）的测试用例 
   
2. 使用参数化完成测试用例的自动生成

3. 在调用测试方法之前打印【开始计算】，在调用测试方法之后打印【计算结束】

> 注意：
> * 使用等价类，边界值，因果图等设计测试用例
> * 测试用例中添加断言，验证结果
> * 灵活使用 setup(), teardown() , setup_class(), teardown_class()

### 作业代码

[pytest_hw_yan](./pytest_hw_yan)

---

### python pytest 测试实战 2

#### 课后作业

1. 补全计算器（加减乘除）的测试用例，编写用例顺序：加-除-减-乘

2. 创建 fixture 方法实现执行测试用例前打印【开始计算】，执行测试用例之后打印【计算结束】

3. 将 fixture 方法存放在 conftest.py ，设置 scope=module

4. 控制测试用例顺序按照【加-减-乘-除】这个顺序执行

5. 结合 allure 生成本地测试报告

### 作业代码

[pytest_hw2_yan](./pytest_hw2_yan)

---

### web 企业微信实战 1

#### 课后作业

1. 使用 cookie 和浏览器复用，实现企业微信的点击客户联系

### 作业代码

[selenium_hw_yan](./selenium_hw_yan)