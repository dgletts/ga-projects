### ***Project 2 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:**  
Great work on this assignment! You made great use of various pandas, and matplotlib functionality. The only direct advice that I have is to keep on practicing and take note of some of the 'tricks' and best practices that you see in class (use them applies!).

**Some notes**  
* In *Question 3*, while it is true that GRE has a larger mean than GPA, it is not the sole reason that the Std. Dev. is greater. If GRE were how it was, but the mean of GPAs was 50000, but it only oscillated between 49999 and 50001, then GRE would still have a much higher Std. Dev. Thus, it is actually about the range of values as well. Scale is important!
* In *Question 10*, as we discussed in class, if you saw that values were skewed in some way, then you can apply some operation to the data to reshape the data and make it more "normal". One of the examples we saw was when values were skewed heavily right, we took the log of the values and this made the data a bit more normal (log-normal), which would help our linear regression learn the output 'better' (because the errors would now be more normally distributed). You can really use any operation (log, square, exponent, inverse, etc.) to reshape the data. Whatever you do, though, you want to make sure you are reshaping the data so that your model can better learn the data (usually because your data now better fits some set of assumptions about the data, like in the OLS case). Let me know if you have any other questions. This is a topic that will come up every time you are working with data.

There are also some tests that you can apply too! Check out the [box-cox test](http://www.statisticshowto.com/box-cox-transformation/).

* Good work filling the missing values with the mean!
