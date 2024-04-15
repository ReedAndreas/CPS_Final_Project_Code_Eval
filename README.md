# CPS_Final_Project_Code_Eval
 
This is our repository for the final code evaluation for AI for CPS. 

## Installation

Because we build off of code from a previous paper there are a few installation requirements but please bear with it and it should all work. Please note you will need a working version of `pip` as well as a python version compatible with the original CRP and RelMax framework (3.9 works well if you can install that). Thanks for your patience!

First of all, please clone this repo.

First you need to download our models as they were too big to host on GitHub (but they are still not too big just >100MB). 
Model1: https://drive.google.com/file/d/1jMWiyEHzELGctD972l5fSkhGrkIR_pkC/view?usp=sharing

Please place these models in the root directory of the project.

Next you need to get CRP and RelMax from the previous paper. CD into the root of the directory, then run:
`git clone https://github.com/rachtibat/zennit-crp`

You will next need to make a virtual env for the project. Do this by running:
`python3.9 -m venv cps_eval_utils`

Now you should be able to run this to install the crp and relmax library you cloned into pip:
`pip install ./zennit-crp`

After that, please run: 
`pip install -r requirements.txt` 
to install the rest of the requirements.

Hopefully you should be good to go now in running the code in the notebooks.

If it gives any error of a library missing try to install it via pip. If that fails feel free to reach me at reed.w.andreas@vanderbilt.edu or 646-884-2406 and I would be happy to help!
