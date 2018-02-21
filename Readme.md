# Machine Learning

## Keras(Python)
	ÄÉ¶ó½º °­ÁÂ
	https://tykimos.github.io/lecture/


## 1.Anaconda installing
	https://www.anaconda.com/download/#windows
	
	All User
	Add Anaconda to the system PATH environment variable

## 2.Add system PATH environment variable
	C:\ProgramData\Anaconda3
    	C:\ProgramData\Anaconda3\Scripts
    	C:\ProgramData\Anaconda3\Library\bin

	Above
	C:\Python27
    	C:\Python27\Scripts
    	C:\Python27\Lib\site-packages

## 3.Check Anaconda and Python
	Window+R for lauching CMD
	
	input >conda --version
	output>conda x.x.xx

	input >python
## 4.Create Project directory
	input > cd c:\
	
	c:\>mkdir Projects
	c:\>cd Projects
	
	c:\Projects>mkdir keras_talk
	c:\Projects>cd keras_talk

	
## 5.Create virtual development environment
	-create virtual development environment
	c:\Projects\keras_talk>conda create -n venv python=3.5 anaconda		
	
	and "y"
	-launching virtual development environment
	c:\Projects\keras_talk>activate venv
	
	output > (venv) c:\Projects\keras_talk>

## 6.Installing Jupyter Notebook
	-install jupyter notebook
	(venv) c:\Projects\keras_talk>conda install -n venv ipython notebook
	
	and "y"


	-launch the jupyter notebook
	(venv) c:\Projects\keras_talk>jupyter notebook

## 7.Installing Package	
	(venv) c:\Projects\keras_talk>conda install -n venv numpy matplotlib pandas pydotplus h5py scikit-learn
    	(venv) c:\Projects\keras_talk>conda install -n venv scipy mkl-service libpython m2w64-toolchain 

## 8.Installing Library
	(venv) c:\Projects\keras_talk>conda install -n venv theano pygpu
    	(venv) c:\Projects\keras_talk>conda install -n venv git graphviz
    	(venv) c:\Projects\keras_talk>conda install -n venv tensorflow

	-keras download and move to keras
	(venv) c:\Projects\keras_talk>git clone https://github.com/fchollet/keras.git
    	(venv) c:\Projects\keras_talk>cd keras
    	(venv) c:\Projects\keras_talk\keras>_	
	
	-Install keras
	(venv) c:\Projects\keras_talk\keras>python setup.py install

## 9.Check Package version
	(venv) c:\Projects\keras_talk\keras>cd ..
    	(venv) c:\Projects\keras_talk>_
    	(venv) c:\Projects\keras_talk>jupyter notebook

