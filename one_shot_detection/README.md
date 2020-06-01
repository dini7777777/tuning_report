# tuning_report

Template for tuning DL road detection experiment report.

-----
### 0. [Experiment goal](#exp_name)
### 1. [Method](#method)
### 2. [Config](#config)
### 3. [Result](#result)
### 4. [Discussion](#discussion)
### 5. [References](#references)
-----



## <div id="#exp_name">Experiment goal</div>

1. Motivation: What Pain points are we trying to solve?
2. Limits: 


## <div id="#method">Method</div>


* **Method name:**

Provide pics if needed.

<div style='text-align:center'><img src='./figure/method_name/pic.png' style='width:300px'></div>



## <div id="#Config">Config</div>

 Infos to **reproduce** the exact experimant result.
 
 
 #### Must have: 
 
 - Repo commit_id:
 - Dataset:
 - Annotation method: 
 - Hyperparameters of model / optimizer / initialize:
    - SSD300
    - backbone: Resnet
    - RMSProp
    - Xaviar


#### Nice to have: 

- Library version:
    - torch==1.5.0
    - Command line: `blablabla command`
    - Saved model checkpoint path: `./path/on/your/device`


## <div id="#result">Result</div>
 
 - Statistics: 
    - Loss?
        - localization
        - classify
    - Acc?
    - Convergence behavior?
     


#### Nice to have: 

- Failure pattern:
    - Failed file names.
    - Visualize inference images
 - Comparasion with other experimants.


## <div id="#discussion">Discussion</div>

Insights, future work.


##### <div id="#references">References:</div>

 - Paper links.
 - Links to the compared exp reports.
