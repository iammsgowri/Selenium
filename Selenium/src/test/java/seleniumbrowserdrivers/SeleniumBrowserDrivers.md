# Browser Drivers

# ChromeDriver Class

## ChromeDriver driver = new ChromeDriver();

```java
ChromeDriver driver = new ChromeDriver();
```

# EdgeDriver Class

## EdgeDriver driver = new EdgeDriver();

```java
EdgeDriver driver = new EdgeDriver();
```


# FirefoxDriver Class

## FirefoxDriver driver = new FirefoxDriver();

```java
FirefoxDriver driver = new FirefoxDriver();
```


```java
package seleniumbrowserdrivers;

import org.openqa.selenium.chrome.ChromeDriver;

public class ChromeBrowserDriver {

	public static void main(String[] args) {

		ChromeDriver driver = new ChromeDriver();
		driver.quit();

		// driver = new EdgeDriver();
		// EdgeDriver cannot be resolved to a type

	}

}
```
```java
Using "CHROMEDRIVER" object "CANNOT CREATE" object for "EDGEDRIVER" class
```



