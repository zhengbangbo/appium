[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
# 获取焦点元素

获取当前会话中的焦点元素
[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
## 用法示例

```java
// Java
WebElement currentElement = driver.switchTo().activeElement();

```

```python
# Python
element = driver.switch_to.active_element

```

```javascript
// Javascript
// webdriver.io example
driver.getActiveElement();

// wd example
let element = await driver.active();

```

```ruby
# Ruby
# ruby_lib example
switch_to.active_element

# ruby_lib_core example
@driver.switch_to.active_element

```

```php
# PHP
// TODO PHP example

```

```csharp
// C#
IWebElement currentElement = driver.SwitchTo().ActiveElement();

```


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
## 版本支持

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
### 服务端

|平台|Driver|平台版本|Appium版本|Driver版本|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/cn/drivers/ios-xcuitest.md) | 无 | 无 | 无 |
|  | [UIAutomation](/docs/cn/drivers/ios-uiautomation.md) | 无 | 无 | 无 |
| Android | [UiAutomator2](/docs/cn/drivers/android-uiautomator2.md) | 无 | 无 | 无 |
|  | [Espresso](/docs/cn/drivers/android-espresso.md) | 无 | 无 | 无 |
|  | [UiAutomator](/docs/cn/drivers/android-uiautomator.md) | 无 | 无 | 无 |
| Mac | [Mac](/docs/cn/drivers/mac.md) | 无 | 无 | 无 |
| Windows | [Windows](/docs/cn/drivers/windows.md) | 无 | 无 | 无 |


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
### Appium客户端

|编程语言|支持的版本|对应的文档|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| 全部 | [seleniumhq.github.io](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebDriver.TargetLocator.html#activeElement--) |
|[Python](https://github.com/appium/python-client/releases/latest)| 全部 | [selenium-python.readthedocs.io](http://selenium-python.readthedocs.io/api.html?highlight=active_element#selenium.webdriver.remote.webdriver.WebDriver.switch_to_active_element) |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| 全部 |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| 全部 | [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L1934) |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| 全部 | [www.rubydoc.info](https://www.rubydoc.info/gems/selenium-webdriver/0.0.28/Selenium/WebDriver/TargetLocator#active_element-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| 全部 | [github.com](https://github.com/appium/php-client/) |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| 全部 | [github.com](https://github.com/SeleniumHQ/selenium/blob/master/dotnet/src/webdriver/Remote/RemoteTargetLocator.cs) |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
## HTTP应用程序接口文档

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
### 接口

`POST /session/:session_id/element/active`

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
### URL参数

无

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
### JSON参数

无

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
### 返回结果

定位到的元素的JSON对象(`object`)

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/other/active.yml)
## 其他链接

* [W3C 文档](https://www.w3.org/TR/webdriver/#get-active-element)
* [JSONWP 文档](https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol#sessionsessionidelementactive)
