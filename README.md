This repository contains the information and code for the CS8395 AI in CPS class project.

Author: Reed Andreas, Gloria Zhang

## Enhancing Domain Adaptation in AI Models through Explainable AI Techniques: A CRP and RelMax Approach

### Installation

Because we build off of code from a previous paper there are a few installation requirements but please bear with it and it should all work. Please note you will need a working version of `pip` as well as a python version compatible with the original CRP and RelMax framework (3.9 works well if you need a new one but otherwise your current one should be fine so long as nothing conflicts when you install via pip). Thanks for your patience!

First of all, please clone this repo.

Then, you need to download our models as they were too big to host on GitHub (but they are still not too big just >100MB). 
Model1: https://drive.google.com/file/d/1jMWiyEHzELGctD972l5fSkhGrkIR_pkC/view?usp=sharing

Please place these models in the root directory of the project.

Next you need to get CRP and RelMax from the previous paper. CD into the root of the directory, then run:
`git clone https://github.com/rachtibat/zennit-crp`

You will next need to make a virtual env for the project. Be sure to do this with the proper python version you have pre-selected. Do this by running:
`python -m venv cps_eval_utils`
OR 
`python3.9 -m venv cps_eval_utils` if you have multiple version of python and want to select one in particular.

Then you should activate this env by running:
`source cps_eval_utils/bin/activate`

Now you should be able to run this to install the crp and relmax library you cloned into pip:
`pip install ./zennit-crp`

After that, please run: 
`pip install -r requirements.txt` 
to install the rest of the requirements.

Again for all of these pip installs please be sure you use the proper version of pip. If any particular library fails you can try running the first import cell of our code and you can manually install whatever python says you need. Also be sure your pip version is correct (should be similar to python 3.9 pip) if anything is not working.

Pytorch can be a bit weird to install the first time so if it is not working please refer to this link `https://pytorch.org/get-started/locally/` or reach out to me at the contact info at the bottom.

Hopefully you should be good to go now in running the code in the notebooks. 
The first notebook to try is `demo_experiment_1.ipynb`
Feel free to run cell by cell or hit run all (reccommended) to view the results.
Running everything from experiment1_demo.ipynb will likely take between 5-45 minutes depending on the speed of your machine. If you have any problems with timing please reach out at contact info below!

If it gives any error of a library missing try to install it via pip. If that fails feel free to reach me at reed.w.andreas@vanderbilt.edu or 646-884-2406 and I would be happy to help!

Your results should be similar to ours but we also tried to make the computation take less long so the test size is relatively small (100). If desired, go find where that is (we commented it so its clear) and feel free to up the size so that you achive more precise results, but requiring more computation.
