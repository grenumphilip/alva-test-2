# Chicago Crime Analysis - Level 1

This task evaluates your ability to analyse a dataset and report your findings effectively. Your goal is to complete all tasks outlined in the accompanying [TODO.md](TODO.md) file. 

## If you run into a problem

Need help? Head over to [our community on GitHub](https://github.com/orgs/DevSkillsHQ/discussions/categories/help) to get assistance.

## Before you get started

The target dataset is hosted in BigQuery. We recommend you to use the BigQuery interface to access and run queries, but you may also download the data and use other tools you are familiar with.

<details>
  <summary>Configure your SQL environment with BigQuery</summary>

### Instructions

To configure your BigQuery environment, please follow the steps below:

1. Go to https://console.cloud.google.com (If you don't have a GCP account, please create it - it's free of charge).
  
  ![139556648-93b10fa1-3831-4588-a885-b2a340192a78](https://user-images.githubusercontent.com/1162212/139659491-9db1a0ab-d89a-498a-8dcd-b44b00941c10.png)
  
2. Create a new project.
  
  ![139556727-30259ece-4e3c-43d4-91a9-b78e0d827d2c](https://user-images.githubusercontent.com/1162212/139659586-3e1848f5-4ae1-4ff0-9573-de4c57bc3044.png)
    
3. Click on [this link](https://console.cloud.google.com/marketplace/product/city-of-chicago-public-data/chicago-crime) to navigate to the task data set.
     
4. Click "View Dataset".

![CleanShot 2021-11-01 at 21 37 11](https://user-images.githubusercontent.com/1162212/139738653-66148a31-4e12-4619-b254-0c822675c8ff.png)
  
5. Switch to the "Editor" tab. This is where you can write your SQL queries. The tables that you query can then be saved for manipulating data using other tools. 

![CleanShot 2021-11-01 at 21 45 11](https://user-images.githubusercontent.com/1162212/139739768-9536932a-fd69-4b3c-97a2-0a98b9c232c7.png)
  
6. You're ready to go! Best of luck!

</details>

## Visualise data in BigQuery

We recommend you to use the Explore Data feature found in BigQuery to visualise your data. 

<details>
  <summary>Visualise data using Google Sheets</summary>

### Instructions
  
1. Write your query and click to "Run"
  
![image](https://github.com/ffc1e12/insight-edge-b5igj/assets/97436324/90488e44-eff0-464e-8fbc-91d10a53f8b5)
 
2. Click "Explore Data" and select the tool you want to use. We suggest the "Explore with Sheets" option.

![image](https://github.com/ffc1e12/insight-edge-b5igj/assets/97436324/b748e3fd-ab37-48bb-91f2-f66a44f42bd6)

3. You will be directed to Google Sheets, there click on "Charts"
<img width="519" alt="image" src="https://github.com/ffc1e12/insight-edge-b5igj/assets/97436324/8183a413-4cc3-4cae-8fec-837f07c8c0a8">
<br/>
<img width="414" alt="Screenshot 2023-06-21 at 12 57 54" src="https://github.com/ffc1e12/insight-edge-b5igj/assets/97436324/c1e8f399-806c-4f47-86d9-dcbbfca8e94d">
<br/>
<br/>

4. Visualize the data using the UI. 
<img width="930" alt="image" src="https://github.com/ffc1e12/insight-edge-b5igj/assets/97436324/1db69524-4888-4ab5-b1e0-40486312ea0a">
<br/>

5. Either export the graph as a PDF or link to it from your submitted responses (remember to ensure that reviewers must have access to view the graph). 

</details>

<details>
  <summary>Visualise data using Looker studio</summary>

### Instructions 

1. Write your query and click to "Run"
  
![image](https://github.com/ffc1e12/insight-edge-b5igj/assets/97436324/90488e44-eff0-464e-8fbc-91d10a53f8b5)

3. Click "Explore data" and select "Explore with Looker Studio".

![image](https://github.com/DevSkillsHQ/chicago-crime-analysis-v2-level-1/assets/118350803/d7fe8fef-fb16-4a88-8af0-9269a133de2e)

4. You'll be directed to Looker Studio with the queried data loaded. From here you can add grahps or tables via the UI.  

![image](https://github.com/DevSkillsHQ/chicago-crime-analysis-v2-level-1/assets/118350803/afb86afc-8b2d-4165-a874-077d17df50ba)

5. To save your charts you can take screenshots of the charts and add them to your repository or export as a PDF. 
  
</details>

<details>
  <summary>Visualise data using Colab notebook</summary>

### Instructions 

Colab Notebooks allow you to write and execute Python code and build your own graphs and tables, for example using Pandas and Matplotlib. 
1. Write your query and click to "Run"
  
![image](https://github.com/ffc1e12/insight-edge-b5igj/assets/97436324/90488e44-eff0-464e-8fbc-91d10a53f8b5)

2. Click "Explore data" and select "Explore with Colab Notebook".

![image](https://github.com/DevSkillsHQ/chicago-crime-analysis-v2-level-1/assets/118350803/d7fe8fef-fb16-4a88-8af0-9269a133de2e)

3. You'll be directed to a new Colab Notebook. The notebook includes boilerplate code to get you going. Do note that you need to exectue the first script titled **Setup** to authenticate your environment.
 
![image](https://github.com/DevSkillsHQ/chicago-crime-analysis-v2-level-1/assets/118350803/858b990a-6b5c-47bc-bdbf-e53f84875824)

4. Follow the next steps outlined in the notebook and you'll be ready to start building your graphs.

5. You can share your graphs as screenshots pasted along with your submission or share the notebook as part of your submission. To do this, got _File_ ➞ _Save Copy in Drive_. Remember to set correct sharing permissions and include a link to the notebook as part of your submission. 
  
</details>

## What we expect from you

1. Complete the tasks outlined in the accompanying [TODO.md](TODO.md) file. Edit it to include your answers. Feel free to upload any additional files with the visualizations (if you edit [TODO.md](TODO.md) using the GitHub web interface, drag and drop your image and it'll be uploaded and embedded automatically). 
2. Save the changes on a new branch called `implementation`.
3. Create a new pull request from your newly created `implementation` branch, but **please do not merge it**.
4. Await further instructions from the hiring team.

## Time estimate

Between **1-2 hours** depending on your experience level.

Also, there is no countdown. The estimate is for you to plan your time.

---

Authored by [Alva Labs](https://www.alvalabs.io).
