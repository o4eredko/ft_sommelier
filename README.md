# ft_sommelier
It is a Unit Factory educational machine learning project. The main goal is to to create a single neuron, that will be able to distinguish between high and low quality wines, based on their chemical elements.

### Constraints
* The project must be written in Python
* The only allowed libraries are: matplotlib, pandas, and the standard python libraries.
* It's forbidden to use DataFrame math/matrix methods (i.e. ‘.T’, ‘.transpose’, ‘.dot’, ‘.divide’, etc...)
* It's forbidden to directly import and use libraries like: numpy, scipy, scikitlearn, tensorflow, etc...

### Subject
You can find the whole subject inside the **resources** directory.

Long story short, the project contains 6 mandatory parts and 3 bonus parts. Most of them are done and can be found in **main.ipynb** file inside the **notebooks** folder
The main tasks are to create a **Perceptron** and an **Adaline** neurons to recognize good wines.
File **main.ipynb** will move you through the whole subject and the documentation for each function will show how to use them.

### Prerequisites
Docker daemon installed and run

### Installation and running
```
docker build -t ft_sommelier .
docker volume create notebooks
docker run -it -p 8888:8888 -v notebooks:/notebooks ft_sommelier

Then open the link in your browser:
<docker-host-ip>:8888/?token=...%
```
