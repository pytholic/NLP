# Stanford CS234N

## Depedndency Parsing

* **Arc** is drawn frrom **Dependent** to the **head**
* `Dependent` is the thing that **modifies** or further **specifies** or **attaches** to the `head`.

---
## Neural Networks
* **Exponential non-linearities** i.e. *sigmoid* and *tanh*, are slow and expensive to compute. So people started experimenting with simpler non-linearities. However, these non-linear function have `saturation region`.
*  **ReLU** is the simplest kind of non-linearity. It is the most successful non-linearity in neural networks. There are further variants or ReLU e.g. **Leaky ReLU** and **Parameteric ReLU**.
*  Neural network matrices must be initialized with **small random values**. Otherwise, it won't learn and solution will be bad.


---
## Language Modeling
In NLP, **Lnaguage modeling** is the task of predicting what word comes next. 
* It is a `probability distribution` over next words given a preceeding context.
  
* Traditional method (pre- deep learning) that powered `speech recognition` and other applciations for atleast a couple of decades was **n-gram language models**.
* * **n-gram** is a chunk of n consecutive words.



---
## Notes
* Try to use **vectors** and **matrices** instead of **for loops**. This gives speed boost.