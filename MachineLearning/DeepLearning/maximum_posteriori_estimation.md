## maximum a posteriori estimation(MPE)

![MPE](./img/MPE.png)

It was suggested to redeem the [MSE](cross_entropy.md).

If you use MLE, it will find the theta(parameters) that only can fit to the given data. However, if you use MPE, you can get parameters for more general situations. Sadly, to calculate the MPE, you need ![simple_form](./img/f_theta_given_X.png), but what we have is only ![simple_form2](./img/f_X_given_theta.png) and we use [Bayes’ Theorem](../Math/bayes_theorem.md). 
