<div align="center">

## Swap Magic


</div>

### Description

Do you think it is possible to swap values between two variables without using a third temporary variable? What? No? Yes? Well, the answer is...YES. Take a look at the code and don't forget to vote!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[FAzle AreFin](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/fazle-arefin.md)
**Level**          |Beginner
**User Rating**    |4.7 (28 globes from 6 users)
**Compatibility**  |Java \(JDK 1\.1\), Java \(JDK 1\.2\)
**Category**       |[Calculators & Science](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/calculators-science__2-71.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/fazle-arefin-swap-magic__2-2973/archive/master.zip)





### Source Code

```
/*
	Swap Magic
	Swaps values between two variables without using a third temporary variable
	Programmer: Fazle Arefin
*/
public class SwapMagic {
	public static void main(String args[]) {
		// declare and initialize two variables
		int a = 10;
 		int b = 20;
 		System.out.println("Before swapping a = " + a + " and b = " + b);
 		a = a + b;
 		b = a - b;
 		a= a - b;
 		/*
 			instead of + and - you can use * and / respectively
 			a = a * b;
 			b = a / b;
 			a= a / b;
 			instead of + and - or * and / you can use the XOR operator ^
 			but this restricts you to only swapping integers
 			a = a ^ b;
 			b = a ^ b;
 			a= a ^ b;
 		*/
 		System.out.println("Before swapping a = " + a + " and b = " + b);
 }
}
```

