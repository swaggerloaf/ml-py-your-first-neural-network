# ml-py-your-first-neural-network
Using Visual Studio Code and numpy create your first neural network 

This is a guide to get you up and running. I'm on a mac but windows should be very similar. 

1.Install the Python development environment on your system (3.7) go to python.org and install, the default install on mac isn't good enough. 

2. install virtualenv   this allows you to do everything in a local virtual env and be able to clean up easy afterwards.
<code>sudo pip3 install -U virtualenv</code>

3. check your installs
<code>python3 --version</code>

<code>pip3 --version</code>

<code>virtualenv --version</code>

4. Clone this github repository:
<code>git clone https://github.com/swaggerloaf/ml-py-your-first-neural-network.git</code>
 and in that directory create a virtual envirnment by running:
<code>virtualenv --system-site-packages -p python3 ./venv</code>

5. Now execute the enviornment
<code>source ./venv/bin/activate</code>

6. Open the directory first_nn with visual studio code

7. Select the python virtual env  use the Python: Select Interpreter command from the Command Palette (⇧⌘P)
<code>https://code.visualstudio.com/docs/python/environments</code>

8. open integrated terminal The environment is activated automatically when you use the Terminal: Create New Integrated Terminal command 

9. In the terminal do the following:

<code>pip install --upgrade pip</code>
<pre> pip list
Package    Version
---------- -------
pip        19.2.1 
setuptools 41.0.1 
virtualenv 16.7.2 
wheel      0.33.4 
</pre>


Install pytorch since it installs numpy for us and we will be using it eventually. 
<code>pip3 install torch torchvision</code>

<code>pip list</code>
