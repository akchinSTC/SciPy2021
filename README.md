## Welcome to SciPy2021 !

## Create and Explore Data Pipelines with Elyra and JupyterLab
### Alan Chin - Software Engineer - IBM

### Interactive Tutorial
- Try out Elyra with Binder, no installation necessary!  
  [![Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/akchinSTC/SciPy2021/main?urlpath=lab)
  and try out our [Pipeline Editor Tutorial](https://github.com/elyra-ai/examples/tree/master/pipelines/hello_world_kubeflow_pipelines)
- If you have any questions or experience any issues, please open an issue [HERE](https://github.com/akchinSTC/SciPy2021/issues) 
or reach out on our [gitter](https://gitter.im/elyra-ai/community#integrations)!
  

### Introduction to Elyra
The goal of using Elyra is to help provide users with a low-code/no-code solution to creating data pipelines in 
Apache Airflow and Kubeflow Pipelines on Kubernetes. We surface concepts and patterns common in pipeline construction 
into a familiar, easy-to-navigate interface for Data Scientists and Engineers, so they can create pipelines on their own
without having to learn another additional layer of code. 

Elyra at its core, is a curated collection of JupyterLab UI and server extensions, designed to compliment each other
and is completely Open Source.

### Notebook based pipelines
![Notebook Pipelines](images/Slide7.jpeg?raw=true)  

Elyra primarily uses Jupyter notebooks(Python and R Scripts as well) to control the flow of data in the pipeline 
in the form of nodes. Notebooks were selected because they are used extensively in the Data Science Community 
and are well represented at many levels and software related professions. They are easy to understand and can 
tell a "Story" well due to how they encompass units of work iteratively.  

![Notebook Pipelines](images/Slide8.jpeg?raw=true)  

We incorporate the use of containers to satisfy any framework or library requirements that these notebooks might need, 
which now as a whole resembles a Kubernetes pod...and while the bulk of the work logic is handled by notebooks and scripts, 
we still need code to handle the orchestration of these nodes. 

![Learning the Layer](images/Slide13.jpeg?raw=true)  

Elyra aims to make this layer of orchestration code transparent to the user. No need to learn how to use workflow SDKs or
DSL. Just drag your notebook/scripts into the pipeline editor, connect them in the order you want them to execute, 
hit run, and Elyra does the rest. In the following example, we can follow what happens after a pipeline is created
in the pipeline edition and executed in Kubeflow Pipelines.

![Kubeflow Pipelines Execution](images/Slide18.jpeg?raw=true)


### Exciting new features coming in next release
- Pipeline native component/operator support - In additional to notebook/script based pipelines, we are adding runtime 
  component specific support for both Apache Airflow and Kubeflow Pipelines
- Refreshed visual pipeline editor

### For more information about Elyra, please check out:
- [Elyra Official Documentation](https://elyra.readthedocs.io/en/latest/)
- [Elyra on Github](https://github.com/elyra-ai/elyra)
- [Additional Elyra Pipeline Examples](https://github.com/elyra-ai/examples)