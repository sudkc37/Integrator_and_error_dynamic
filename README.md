# Integrator_and_error_dynamics

Assumption:
We have a function 'sin(t)**3 + (exp(t)**-6) * 2' that mimics the real-time price in short intervals of time:

#Error Analysis of Numerical Differentiation on Function.
-- Using the first Principle df/dx ~ (f(T + deltaT) - f(T))/ delta T. Forward, Backward, and central differences have been derived.
where,

forward difference = df/dx ~ (f(T + deltaT) - f(T))/ delta T

backward difference = (f(T) - f(T - deltaT)/ delta T

Using the Taylor series Expansion, the forward and  backward difference have the same error scaling the leading error term is delta T i.e. (d^f/dt^2)*deltaT/2! 
