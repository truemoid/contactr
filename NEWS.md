# 0.1.0

* First release

# 0.2.0

* Rewrite of contact analysis data function. Avoids lengthy case_when
  but uses nested for loops.
* Add new function for producing basic plot.
* Add example dataset 'dholes' used in function documentation examples.
* Add code of conduct for contributions.

# 0.2.1

* Improved example for `contact_data`.
* Bug fix: correct reporting of number of samples.
* Make sure 2 samples in drillhole.
* `contact_data` now requires a matrix of contact pairs rather than evaluating
all possible pairs, which is very slow.
