# Install Tensorflow with Anaconda

1. Follow the instructions on the [Anaconda website](https://www.anaconda.com/download/#macos)
2. Create a conda environment and name it as you wish (e.g. tensorflow) by invoking the command:
	`conda create -n tensorflow`
3. Activate the "tensorflow" environment that has been created
	`conda activate tensorflow`
	Later, if you wish deactivate
	`conda deactivate`
4. Install Tensorflow by one of the following commands
	`pip install tensorflow`
	`pip install --ignore-installed --upgrade   
 https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.9.0-py2-none-any.whl`

# Validate your installation

 1. Inside your "tensorflow" enviroment, invoke python
	 `python`
 2. Run this short program
	```
	import tensorflow as tf
	hello = tf.constant('Hello, TensorFlow!')
	sess = tf.Session()
	print(sess.run(hello))
	```
 3. Your installation is working if the system can print out the message
  `Hello, Tensorflow!`
	 
# Use Jupyter notebook as your interactive IDE

1. As you install Tensorflow with Anaconda, you can start your [notebook ](http://jupyter.org/) as follows
  `jupyter notebook`
2. Read the [docs](https://jupyter-notebook.readthedocs.io/en/stable/) to be familiar with the notebook interface 
3. Your mini adventure, explore [Google Colab](colab.research.google.com) as the alternative development environment 
