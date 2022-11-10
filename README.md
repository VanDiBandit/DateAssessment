# DateAssessment
Using Command Prompt(Windows) To get current date and time

Sources:

https://www.instructables.com/Programing-with-Java-using-Command-Prompt/
https://www.javatpoint.com/java-get-current-date
https://www.wikihow.com/Compile-%26-Run-Java-Program-Using-Command-Prompt
https://www.watchingthenet.com/how-to-navigate-through-folders-when-using-windows-command-prompt.html

Code:
```
import java.time.LocalDateTime;  
import java.time.format.DateTimeFormatter;  
    
public class CurrentDateTime   
{      
  // main method  
  public static void main(String[] argvs)   
  {      
    // creating a new object of the class Date  
    java.util.Date date = new java.util.Date();    
    System.out.println("Today is:"+ date);   
       
  }      
}  
```
