## Volatility-Smile
The notebook contains the Volatility Smile. <br />
<br />
**Objective:** To prove that Black-Scholes assumption of constant Implied Volatility is wrong by plotting the graph between Implied Volatility and Strike Price. The resulting graph is in the shape of a smile. <br />
<br />
I calculated the Implied Volatility in 3 ways: <br />
1) **Newton-Raphson Method**. <br />
2) **Bisection Method**. <br />
3) I used the **Mibian** package to calculate the Implied Volatility. <br />
<br />
I found that Newton - Raphson was the best approximation in all the 3. <br />
<br />
I observed it by using the Implied Volatility in Black-Scholes formula obtained from Newton-Raphson. It had a worst approximation of error 10^(-5) percentage and the best approximation to be having an error of 10^(-13) percentage.
<br />
<br />
The stock chosen was SBIN which is State Bank of India. I chose the Call Option data. <br />
<br />
If you have any query please be free to contact me sairam.ravuri@stonybrook.edu

