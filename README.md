# ml-tutorial
A short repository of example notebooks for introductory ML. A video of the associated presentation for the CHIMERAS workshop and discussion is available [on youtube](https://www.youtube.com/watch?v=P7uidiRR_d8).

## 1) Download miniforge
[miniforge](https://conda-forge.org/download/) is a lightweight conda platform for the ```conda::forge channel``` specifically. It can handle automatic downloading of python and its associated packages, and we will use it to set up the environment so that you can be sure you've got everything you need to run the examples. If you've got conda-forge or anaconda installed already, that works too.

## 2) Download this repository
You can download and extract the zip or clone this repository. The dropdown on the top-right has a "download zip" option, and if you're comfortable with git you'll know you can also run ```git clone https://github.com/apt-get-nat/ml-tutorial.git```

## 3) Build the environment
Open the miniforge prompt, navigate into the directory and run ```conda env create -f environment.yml```

## 4) Run the examples and follow along
Activate the environment by running the command ```conda activate ml-tutorial``` in the miniforge prompt, and then open jupyter with the command ```jupyter lab```. This opens an application where you should see a file tree on the left panel. If you're running miniforge from inside the tutorial directory, the .ipynb notebook files should be right there! Otherwise, you might have to navigate your computer's file system to find them. You can double-click on a notebook file to open it, and from there you can run the code one cell at a time, and tweak things to see what breaks. Coding is all about breaking things!
