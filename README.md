# python3-course-notebooks


A Python 3 course provided through Jupyter Notebooks.


## How to use the course

Open a terminal and install all the required dependencies

    sudo apt-get install -y python3-pip
    pip3 install --upgrade pip
    pip3 install notebook ipython jupyter
    sudo apt-get install -y git
    echo "export PATH=$PATH:~/.local/bin" >> ~/.bashrc

Then clone this repository in your home

    cd $HOME
    git clone https://github.com/alsora/python3-course-notebooks

Open a terminal in the directory that you just created and start Jupyter

    jupyter notebook

This will open a Browser window, where you will see the content of this repository.
Select an exercise folder and open the file terminating in `.ipynb`.


## Updating the course

Once in a while, new lessons may be added to the course.
In order to get them, open a terminal in the course directory

    git pull

