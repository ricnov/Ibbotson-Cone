# Ibbotson-Cone

The Ibbotson Cone [R. G. Ibbotson and P. Chen. Long-run stock returns: Participating in the real economy. Financial Analysts Journal, 59(1):88–98, 2003.], or Volatility Cone, is a graphical representation of the expected return and risk of an investment portfolio over time. The cone makes it possible to describe, in probabilistic terms, the evolution of the portfolio by contextually representing in a single graph the evolution in a worst-case scenario, in a best-case scenario, and in the median scenario.

The Ibbotson Cone is characterized by two parameters:
- **confidence level**: it is the probability that the portfolio price evolution is under the values of the worst-case scenario;
- **protection level**: it is the probability that the portfolio price evolution is between the values of the best-case scenario and the worst-case scenario.

The cone of the replica portfolios built using Model 1 and the two set of factors are shown in Figure 7.13 and Figure 7.14. They are built on the first month of the test set, namely May 2017; the levels chosen are 2.5% for the confidence level and 5.0% for the protection. The curves representing the best-case and worst-case scenario are calculated using the assumption of normality of the returns and the equations are the following:

WorstCase\(_t\) = Δt ∗ μ - √Δt ∗ σ ∗ N\(^{-1}\)(α)

BestCase\(_t\) = Δt ∗ μ + √Δt ∗ σ ∗ N\(^{-1}\)(α) 

where:
- Δt is the time interval between the initial time and t;
- μ is the mean of the portfolio, composed with the initial weight
- σ is the standard deviation of the portfolio, composed with the initial weights
- α is the percentage equal to 100% - confidence level.

The curve representing the average-case is calculated considering only the first part of the equation:

AverageCase\(_t\) = Δt ∗ μ.
