# Feed Reader Test

---

### 项目详情
 
 - 使用Jasmine测试
 - 测试侧边栏隐藏及显示功能
 - 测试ajax请求是否按照预期

### 使用

  下载zip文件打开index.html文件查看Jasmine测试结果

### 参考

- describe函数定义测试套件，描述测试
- it函数定义具体测试，测试由it函数调用
- beforeEach函数定义每个测试套件测试开始前运行的代码，其他还有afterEach, beforeAll, 以及afterAll函数
- expect函数接收一个值，链接一个判断函数，判断expect值是否符合判断函数的期望

#### Matchers

- 每一个matcher都会根据expect函数的接收值与实际值返回布尔值，jasmine根据布尔值判断测试是否通过

#### 异步测试

- jasmine内函数根据done函数判断是否进入下一步测试
- 多个测试应当在异步函数内部或者在jasmine不同生命周期函数调用保证异步函数完成的先后顺序符合预期
