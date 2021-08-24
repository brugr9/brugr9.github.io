# Unreal Engine Plugin: ESB Messaging - Testing

## Install Anaconda
Choose one of these installation methods:

* Via Download; [Anaconda Individual Edition](https://www.anaconda.com/products/individual) or
* Via PowerShell using [chocolatey](https://chocolatey.org/packages/anaconda3): `choco install anaconda3`

## Create Virtual Environment and Install jupyter Notebook
Using Anaconda Navigator:

1.  In tab 'Environments', create new environment named 'ESB' (Python 3.8)
2.  In tab 'Home', dropdown 'Applications on' select the newly created environment 'ESB'
3.  In tab 'Home', from the listed applications install jupyter Notebook
4.  In tab 'Environments', 'ESB', install packages: pyzmq, jsonschema, scipy, ipywidgets

![Screenshot of Anaconda Navigator Tab Environments](./Docs/ScreenshotAnacondaNavigatorEnvironments.jpg "Screenshot of Anaconda Navigator Tab Environments")

## Startup jupyter Notebook
Using Anaconda Navigator:

1.  In tab 'Home', dropdown 'Applications on' select the newly created environment 'ESB'
2.  In tile 'jupyter Notebook' click button 'Launch'
3.  In the browser tab running jupyter, jupyter dashboard tab 'Files' find UE4-Plugin folder 'ESB/Testing'
4.  Start a notebook by clicking on a listed *.ipynb file

![Screenshot of Anaconda Navigator Tab Home](./Docs/ScreenshotAnacondaNavigatorHome.jpg "Screenshot of Anaconda Navigator Tab Home")

![Screenshot of Jupyter Notebook Files](./Docs/ScreenshotJupyterFiles.jpg "Screenshot of Jupyter Notebook Files")

![Screenshot of Jupyter Notebook ESB ZeroMQ Publish](./Docs/ScreenshotEsbZmqPub.jpg "Screenshot of Jupyter Notebook ESB ZeroMQ Publish")
