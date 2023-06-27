# selenium-singularity
Selenium python package with dirvers.

## Drivers

Selenium requires a driver to interface with the chosen browser. Firefox, for example, requires geckodriver, which needs to be installed before the below examples can be run. Make sure it’s in your `PATH`, e. g., place it in `/usr/bin` or `/usr/local/bin`.

Failure to observe this step will give you an error `selenium.common.exceptions.WebDriverException`: `Message`: `geckodriver` executable needs to be in `PATH``.

Other supported browsers will have their own drivers available. Links to some of the more popular browser drivers follow

* [Chromium](https://chromedriver.chromium.org/downloads)
* [Edge](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/)
* [Firefox](https://github.com/mozilla/geckodriver/releases)
* [WebKit](https://webkit.org/blog/6900/webdriver-support-in-safari-10/)
