# BigDecimal Java 

Note: Either exists BigInteger.

<strong>Use this class to work with Currency</strong>

```java
import java.math.BigDecimal;

public class AnyName{
  public static void main(String[] args){
    BigDecimal amount = new BigDecimal("12.34");
    System.out.println(amount);
    
    // Performing calculations
    BigDecimal taxPercent = new BigDecimal("0.1");
    BigDecimal taxAmount = amount.multiply(taxPercent);
    System.out.println("Tax amount: " + taxAmount);
    
    BigDecimal totalAmount = amount.add(taxAmount);
    System.out.println("Total amount: " + totalAmount);
  }
}
