import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;


public class TestCaseForChrome {

	public static void main(String[] args) throws InterruptedException{
		
		System.setProperty("webdriver.chrome.driver", "C:\\Users\\--------\\------\\------\\selenium installation req\\chromedriver_win32\\chromedriver.exe");
		WebDriver driver = new ChromeDriver();
		//launch the page
		driver.get("https://registry.acsnsqip.org/login.html");
		driver.manage().window().maximize();
		Thread.sleep(5000);
		
		//Login
		driver.findElement(By.name("j_username")).clear();
		driver.findElement(By.name("j_username")).sendKeys("----------");
		driver.findElement(By.name("j_password")).clear();
		driver.findElement(By.name("j_password")).sendKeys("-----------");
		driver.findElement(By.xpath("//*[@class='submitBtn'][@value='enter']")).click();
		
		//Verify the links
		driver.findElement(By.xpath("//*[@id='quick']/table/tbody/tr[5]/td/a")).click();
		Thread.sleep(3000);
		driver.findElement(By.xpath("//*[@id='quick']/table/tbody/tr[6]/td/a")).click();
		Thread.sleep(3000);
		driver.findElement(By.xpath("//*[@id='quick']/table/tbody/tr[7]/td/a")).click();
		Thread.sleep(3000);
		
		
		//click on the cases by cycle : first
		System.out.println("clicking on the first link "+driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[6]/td[2]/a")).getText());
		driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[6]/td[2]/a")).click();
		Thread.sleep(1000);
		System.out.println(driver.getCurrentUrl());
		System.out.println(driver.getTitle());
		Thread.sleep(1000);
		driver.navigate().back();
		
		//click on the cases by cycle : second 
		System.out.println("clicking on the first link "+driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[7]/td[2]/a")).getText());
		driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[6]/td[2]/a")).click();
		Thread.sleep(1000);
		System.out.println(driver.getCurrentUrl());
		System.out.println(driver.getTitle());
		Thread.sleep(1000);
		driver.navigate().back();
		
		//click on the cases by cycle : third 
		System.out.println("clicking on the first link "+driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[8]/td[2]/a")).getText());
		driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[6]/td[2]/a")).click();
		Thread.sleep(1000);
		System.out.println(driver.getCurrentUrl());
		System.out.println(driver.getTitle());
		Thread.sleep(1000);
		driver.navigate().back();
		
		//click on the cases by cycle : fourth 
		System.out.println("clicking on the first link "+driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[9]/td[2]/a")).getText());
		driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[6]/td[2]/a")).click();
		Thread.sleep(1000);
		//command to get the current page URL
		System.out.println(driver.getCurrentUrl());
		//command to get the current page title
		System.out.println(driver.getTitle());
		Thread.sleep(1000);
		//command to go back to the previous page
		driver.navigate().back();
		
		//click on the cases by cycle : fifth 
		System.out.println("clicking on the first link "+driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[10]/td[2]/a")).getText());
		driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[6]/td[2]/a")).click();
		Thread.sleep(1000);
		System.out.println(driver.getCurrentUrl());
		System.out.println(driver.getTitle());
		Thread.sleep(1000);
		driver.navigate().back();
		
		//click on the cases by cycle : sixth 
		System.out.println("clicking on the first link "+driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[11]/td[2]/a")).getText());
		driver.findElement(By.xpath("//*[@id='cycleCounts']/table/tbody/tr[6]/td[2]/a")).click();
		Thread.sleep(1000);
		System.out.println(driver.getCurrentUrl());
		System.out.println(driver.getTitle());
		Thread.sleep(1000);
		driver.navigate().back();
		
		//Announcements
		System.out.println("clicking on: - "+driver.findElement(By.xpath("//*[@id='userAdmin.news']/table/tbody/tr[2]/td/a")).getText());
		driver.findElement(By.xpath("//*[@id='userAdmin.news']/table/tbody/tr[2]/td/a")).click();
		Thread.sleep(1000);
		driver.switchTo().defaultContent();
		System.out.println("clicking on: - "+driver.findElement(By.xpath("//*[@id='userAdmin.news']/table/tbody/tr[3]/td/a")).getText());
		driver.findElement(By.xpath("//*[@id='userAdmin.news']/table/tbody/tr[3]/td/a")).click();
		Thread.sleep(1000);
		System.out.println("clicking on: - "+driver.findElement(By.xpath("//*[@id='userAdmin.news']/table/tbody/tr[4]/td/a")).getText());
		driver.findElement(By.xpath("//*[@id='userAdmin.news']/table/tbody/tr[4]/td/a")).click();
		
		//Incomplete Cases
		System.out.println("clicking on: - "+driver.findElement(By.xpath("//*[@id='formStatus']/table/tbody/tr[2]/td/table/tbody/tr[7]/td[1]/a")).getText());
		driver.findElement(By.xpath("//*[@id='formStatus']/table/tbody/tr[2]/td/table/tbody/tr[7]/td[1]/a")).click();
		Thread.sleep(1000);
		driver.navigate().back();
		Thread.sleep(1000);
		
		System.out.println("clicking on: - "+driver.findElement(By.xpath("//*[@id='formStatus']/table/tbody/tr[2]/td/table/tbody/tr[7]/td[1]/a")).getText());
		driver.findElement(By.xpath("//*[@id='formStatus']/table/tbody/tr[2]/td/table/tbody/tr[8]/td[1]/a")).click();
		Thread.sleep(1000);
		driver.navigate().back();
		Thread.sleep(1000);
		
		//documents and resources
		System.out.println("clicking on: - "+driver.findElement(By.xpath("//*[@id='docs']/table/tbody/tr[2]/td/a")).getText());
		driver.findElement(By.xpath("//*[@id='docs']/table/tbody/tr[2]/td/a")).click();
		Thread.sleep(1000);
		driver.navigate().back();
		Thread.sleep(1000);
		
		System.out.println("clicking on: - "+driver.findElement(By.xpath("//*[@id='docs']/table/tbody/tr[3]/td/a")).getText());
		driver.findElement(By.xpath("//*[@id='docs']/table/tbody/tr[3]/td/a")).click();
		Thread.sleep(1000);
		//driver.switchTo().activeElement().click();
		
		System.out.println("clicking on: - "+driver.findElement(By.xpath("//*[@id='docs']/table/tbody/tr[4]/td/a")).getText());
		driver.findElement(By.xpath("//*[@id='docs']/table/tbody/tr[4]/td/a")).click();
		Thread.sleep(1000);
		
		//driver.close(); 
	}
}
