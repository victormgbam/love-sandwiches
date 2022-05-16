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

![lovesandwiches](assets/readme-images/enter2.png 'love sandwiches')
![lovesandwiches](assets/readme-images/enter3.png 'love sandwiches')    

* Your code must be placed in the `run.py` file
* Your dependencies must be placed in the `requirements.txt` file
* Do not edit any of the other files or your code may not deploy properly

## Creating the Heroku app

When you create the app, you will need to add two buildpacks from the _Settings_ tab. The ordering is as follows:

1. `heroku/python`
2. `heroku/nodejs`

You must then create a _Config Var_ called `PORT`. Set this to `8000`

If you have credentials, such as in the Love Sandwiches project, you must create another _Config Var_ called `CREDS` and paste the JSON into the value field.

Connect your GitHub repository and deploy as normal.

## Constraints

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.

-----
Happy coding!