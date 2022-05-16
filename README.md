![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

<h1>LOVE SANDWICHES APP</h1>

Love sandwiches is pyhton app that handles every market day sales for a company that
runs a local market store, that sales that diffrent range of sandwiches.Love sandwich
app handles data input automation for the company by collecting each market day sales,
Calculating surplus for the day and making recommendation for sandwiches for the next day.

<h3>How Love Sandwiches Works</h3>
Love sandwiches app is based on automating sandwiches sales for a company on  market day.
love sandwiches app connect with googlesheet to push data from and into spreadsheet.
Love sandwiches staffs are prompted to enter data to calculate surplus and update stocks. 

<h3>Features</h3>

   <h3>Existing Features</h3>:

    Getting Sales data
    1.Staffs are prompted to enter sales data from last market.
    2.Data should be six numbers and separated by comas.

![Lovesandwiches](assets/readme-images/enter.png 'love sandwiches')

     3. Accept Staff input for six numbers seperated by comas.  


<h3>Input Data Validation and Error-checking></h3>  

    1. Data is validated after six numbers are entered.
    2. Sales worksheet is updated.
    3. Surplus data is calculated and updated.
    4. Stock data worksheet is calculated and updated.

![lovesandwiches](assets/readme-images/enter2.png 'love sandwiches\n')
![lovesandwiches](assets/readme-images/enter3.png 'love sandwiches')    


<h3>TESTING</h3>
    
    I Manually tested the love sandwiches project by following these steps:
       
       1. The code runs and return expected data result.
       2. I passed the code through PEP8 online checker.
       3. I can confirm that there are errors of white trailing spaces.

<h3>Unsolved Bugs</h3>
     
     when I started this project I encountered code errors of trailing white spaces.
     I got tutor assistance on several times by sharing my gitpod workstation. These
     errors were resolved. 

<h3>DEPLOYMENT<h3>
    
    Love sandwiches was deployed through heroku. Steps taken are:

    1.Click on requirement.txt and on the workspace,type pip3 freeze > requirment.txt.
    2.Then commit file to gitpod.
    3.create heroku account by by filling out details.
    4.click on CreateApp and enter Apps name 'Love sandwiches'.
    5.click on the Setting Tab,then config.var to enter CREDS.
    6.Copy CREDS.JSON file and add to heroku.
    7.Click add buildpack, then select PYTHON and save changes.
    8.Again click on add buildpack, select Nodejs and save changes.
    9.Deploy section, click deploy method, select github and connect.
    10. Click deploy.

<h3>CREDITS</h3>
   All the codes used to build love sandwiches project was taken from code Institute
   love sandwiches walkthrough.    