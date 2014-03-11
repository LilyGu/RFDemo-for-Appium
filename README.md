RFDemo-for-Appium
=================
1. Install Robot framework as it's [official website](http://robotframework.org/)  or following [here](http://www.cnblogs.com/GGHHLL/archive/2013/06/07/3123604.html)

2. Install Library used:
   Selenium2Library: pip install robotframework-selenium2library
   RequestsLibrary: pip install -U robotframework-requests

3. Set up [Appium] (http://appium.io/zh-cn/index.html)

  a). clone the appium demo from [github](https://github.com/appium/appium)

  b). download the above robot framework test scripts, put the 'robot' folder under /appium/sample-code/examples/

  c). select the test app(we used UICatalog.app on above), and lunch appium server on http://127.0.0.1 , port 4723


4. Run the test scripts on Robot Framework IDE ride, or use command line:

    cd **/appium/sample-code/examples/robot/Appium
    pybot UIcatalogTest.html
