# MLighter

<br />
<img align="left" src="http://mlighter.freedevelop.org/wp-content/uploads/2022/02/cropped-logo5.png" width="140" height="160"/>

MLighter is a tool for machine learning testing that aims to integrate three testing levels: performance, security and reliability. The tool can be used as a library although it also contains a graphical user interface that aims to connect all the different levels.

The tool also comes with a Docker container to make your life easier. If you want to install it, please follow the instructions underneath.

<br />


## Citation

If you use MLighter, please cite the paper:

*Menendez, Hector D. (2022). Measuring Machine Learning Robustness in front of Static and Dynamic Adversaries. In Measuring Machine Learning Robustness in front of Static and Dynamic Adversaries. IEEE 34rd International Conference on Tools with Artificial Intelligence (ICTAI).*

```
@incollection{menendez2022measuring,
  title={Measuring Machine Learning Robustness in front of Static and Dynamic Adversaries},
  author={Menendez, Hector D.},
  booktitle={Measuring Machine Learning Robustness in front of Static and Dynamic Adversaries},
  year={2022},
  publisher={IEEE 34rd International Conference on Tools with Artificial Intelligence (ICTAI)}
}
```

## Testing Models Reliability.

This section allows to use a model and test its reliability under adversarial conditions. Currently, we allow only models in SKlearn. You just need to include an instance of your input data and test your model directly. Remember that the input needs to respect the models feature space. 

## Testing Bugs in Code.

This part of the tool in based on fuzzing and aims to identify crashes in the code. To run this part you need to create a parametrized template of your code so the fuzzer can start applying different strategies to it. 

## Identifying Performance Issues.

The part extends the previous one to also identify hangs in the code depending on the parameters.

## Graphical User Interface

The User Interface is based on Vue and it is perform in top of a dashboard to make it more flexible for visualization porposes. 
