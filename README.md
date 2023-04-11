### Euler Method
### The Euler method is an approximation method, to predict the value of an equation. A smaller size would lead to better predictions or lesser errors

#### An approach could be defined for the given equation as
$$
\frac{dx}{dt} = f(x), x(0) = x_0
$$

1. Choose a stepsize $$\Delta t$$. Set t = 0
2. Get the number of steps to predict the value to. say `n`
3. For step t=0 using the equation calculate the rate of change $$\frac{dx}{dt} = f(x)$$
4. Use the rate of change from step 3 to determine the next value
    $$ x(t + \Delta t) = x(t) + (\Delta t * \frac{dx}{dt})$$
5. Increase t by the step size $$\Delta t$$
6. Loop to step 2 based on `n`

#### To get the actual value or curve, use 
$$ e^x $$
#### Plot the graphs for various curves with lesser step size
