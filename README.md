# Date-in-java
This is a java program where we can see current date.


package currentdate;
import java.text.DateFormat;
import java.text.SimpleDateFormat;
import java.util.Date;
public class Currentdate {

    public static void main(String[] args) {
        Date date=new Date();
        DateFormat dateformat=new SimpleDateFormat("dd/MM/YYYY");
        String thisdate=dateformat.format(date);
        System.out.println("Today is: "+thisdate);
    }
    
}
