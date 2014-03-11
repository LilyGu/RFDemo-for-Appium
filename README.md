RFDemo-for-Appium
=================
1. Install Robot framework as it's [official Website](http://robotframework.org/)  or following [here](http://www.cnblogs.com/GGHHLL/archive/2013/06/07/3123604.html)

2. Install Library used:
   Selenium2Library: pip install robotframework-selenium2library
   RequestsLibrary: pip install -U robotframework-requests

3. Set up [Appium] (http://appium.io/zh-cn/index.html)

  a). select your test App, we used UICatalog.app on the Demo that Appium provied (https://github.com/appium/appium)

  b).lunch appium server on http://127.0.0.1 , port 4723


4. Run the test scripts on Robot Framework IDE ride, or use command line:

  pybot UIcatalogTest.html
