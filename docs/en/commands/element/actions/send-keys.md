[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
# Send Keys

向元素输入一连串的按键
[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
## 示例用法

```java
// Java
MobileElement element = (MobileElement) driver.findElementByAccessibilityId("SomeAccessibilityID");
element.sendKeys("Hello world!");

```

```python
# Python
self.driver.find_element_by_accessibility_id('SomeAccessibilityID').send_keys('Hello world!')

```

```javascript
// Javascript
// webdriver.io example
$("~SomeAccessibilityId").addValue("Enter");

// wd example
let element = await driver.elementByAccessibilityId("SomeAccessibilityID");
await element.type("Hello world!")

```

```ruby
# Ruby
# ruby_lib example
find_element(:accessibility_id, "SomeAccessibilityID").send_keys("Hello World!")

# ruby_lib_core example
@driver.find_element(:accessibility_id, "SomeAccessibilityID").send_keys("Hello World!")

```

```php
# PHP
$el = $this->byAccessibilityId('SomeAccessibilityID');
$el->setText('Hello world!');

```

```csharp
// C#
MobileElement el = driver.FindElement(MobileByAccessibilityID("Some ID");
el.SendKeys("Some Text");

//Example
MobileElement el = driver.FindElement(MobileById("Some ID");
el.SendKeys("Hello World");

```

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
## 内容描述

可以指定任意的UTF-8字符，然而，如果服务器不支持原生键事件，它应该模拟标准的美国键盘布局的按键。Unicode私有使用区域代码点，0xE000-0xF8FF，用于表示可压入的，非文本键(见下表)。
(有关Unicode字符的信息，请参阅 [Unicode 文档](/docs/en/writing-running-appium/other/unicode.md) )


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
## 支持的语言及平台

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
### Appium Server

|平台|驱动程序|平台版本|Appium版本|驱动版本|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | 9.3+ | 1.6.0+ | All |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | 8.0 to 9.3 | All | All |
| Android | [Espresso](/docs/en/drivers/android-espresso.md) | ?+ | 1.9.0+ | All |
|  | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.3+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | ?+ | 1.6.4+ | All |
| Windows | [Windows](/docs/en/drivers/windows.md) | 10+ | 1.6.0+ | All |


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
### Appium Clients

|语言|支持|文档|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [seleniumhq.github.io](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebElement.html#sendKeys-java.lang.CharSequence...-) |
|[Python](https://github.com/appium/python-client/releases/latest)| All | [selenium-python.readthedocs.io](http://selenium-python.readthedocs.io/api.html?highlight=active_element#selenium.webdriver.common.action_chains.ActionChains.send_keys) |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All | [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L1700) |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All | [www.rubydoc.info](https://www.rubydoc.info/gems/selenium-webdriver/Selenium/WebDriver/Element#send_keys-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| All | [github.com](https://github.com/appium/php-client/) |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| All | [github.com](https://github.com/appium/appium-dotnet-driver/) |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
## HTTP API 规范

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
### 终端

`POST /session/:session_id/element/:element_id/value`

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
### URL 参数

|名字|描述信息|
|----|-----------|
|session_id|ID of the session to route the command to|
|element_id|ID of the element to send keys to.|

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
### JSON 参数

|名称|类别|描述信息|
|----|----|-----------|
| value | `array<string>` | (MJSONWP) The sequence of keys to type. An array must be provided. The server should flatten the array items to a single string to be typed |
| text | `string` | (W3C) A single string to be typed |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
### 响应信息

null

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/actions/send-keys.yml)
## 另请参阅

* [W3C Specification](https://www.w3.org/TR/webdriver/#dfn-element-send-keys)
* [JSONWP Specification](https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol#sessionsessionidelementidvalue)
