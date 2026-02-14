# Student Submission Checklist (Lab 3)

## Report

Epsilon Greedy 
Best performing epsilon = 0.01, with an average reward of 5.47
e = 0.3 is seen shooting upwards initially, getting a great reward, but eventually dips quite a lot too, due to lots of exploration. e = 0.01 gradually climbs up and is the best performing one.

UCB
All the average reward curves appear to be coinciding but c = 1 is the best performing exploration parameter. Best average reward = 5.749

Softmax 
For tau = 1, best reward for the softmax strategy is 5.44

Overall it is observed that UCB achieves the highest reward. 

Random Forest was selected as the classifier due to its strong performance on structured tabular data, ability to model relationships between user behavioral features, and robustness against overfitting. Since accurate context classification is critical for the contextual bandit system, Random Forest provided stable predictions compared to linear models.

The notebook is reproducible after installing the following dependencies;

asttokens==3.0.1
comm==0.2.3
contourpy==1.3.3
cycler==0.12.1
debugpy==1.8.20
decorator==5.2.1
executing==2.2.1
fonttools==4.61.1
ipykernel==7.2.0
ipython==9.10.0
ipython_pygments_lexers==1.1.1
jedi==0.19.2
joblib==1.5.3
jupyter_client==8.8.0
jupyter_core==5.9.1
kiwisolver==1.4.9
matplotlib==3.10.8
matplotlib-inline==0.2.1
nest-asyncio==1.6.0
numpy==2.4.2
packaging==26.0
pandas==3.0.0
parso==0.8.5
pexpect==4.9.0
pillow==12.1.0
platformdirs==4.5.1
prompt_toolkit==3.0.52
psutil==7.2.2
ptyprocess==0.7.0
pure_eval==0.2.3
Pygments==2.19.2
pyparsing==3.3.2
python-dateutil==2.9.0.post0
pyzmq==27.1.0
rlcmab-sampler==1.0.1
scikit-learn==1.8.0
scipy==1.17.0
six==1.17.0
stack-data==0.6.3
threadpoolctl==3.6.0
tornado==6.5.4
traitlets==5.14.3
wcwidth==0.6.0


----

THANK YOU
