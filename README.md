# Challenge 14: Algorithmic Trading

## Model Performances

**Original:** Short SMA: 4, Long SMA: 100, 3 month window

![Actual Returns vs Strategy Returns](https://user-images.githubusercontent.com/86167421/135782232-66487bf5-4e0b-4653-b99e-9328f2b5fd8b.png)

**Tuned 1:** Short SMA: 4, Long SMA: 100, 6 month window

![6 month window](https://user-images.githubusercontent.com/86167421/135783198-7f873203-d5eb-4c31-ac8b-6754f7d44548.png)

**What impact resulted from increasing or decreasing the training window?**
* Decreasing the window affects the algorithm positively by producing more profitable trades. Increasing the window affects the algorithm negatively by producing less profitable trades. 

**Tuned 2:** Short SMA 2, Long SMA 50, 6 month window

![Actual Returns vs Strategy Returns (tuned 2)](https://user-images.githubusercontent.com/86167421/135782934-1066c92d-ccc7-41d8-b873-2caa6f5303d3.png)

**Tuned 3:** Short SMA: 8, Long SMA: 200, 6 month window

![Actual Returns vs Strategy Returns  (tuned)](https://user-images.githubusercontent.com/86167421/135782621-604c505c-3fa8-4f8b-a768-3cfea02fa5f4.png)

**What impact resulted from increasing or decreasing either or both of the SMA windows?**
* It varies... there are many variables involved, i.e. training window and model. In this case, increasing both SMA windows result in less accurate predictions. Decreasing both SMA windows result in better predictions.

**Logistic Regression:** Short SMA: 4, Long SMA: 100, 3 month window

![Actual Returns vs Strategy Returns - Logistic Regression](https://user-images.githubusercontent.com/86167421/135782226-a27b64e3-b2dc-4834-b926-ace115b42d78.png)

**Did this new model perform better or worse than the provided baseline model?**
* The new model performed wrose than the provided baseline model.
