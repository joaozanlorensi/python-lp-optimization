**Job Shop General Solver**  

This folder contains code for a general solver for the Job Shop problem, inspired by [this article](https://developers.google.com/optimization/scheduling/job_shop), from Google OR-Tools.  
The jobs.csv spreadsheets is used to generalize this problem to a situation where you would have a list containing all product parts for building a product along with the machines that they have to go through and the processing time that they would take on each machine. The objective is to build the final product as fast as possible.  
The product parts listed in the jobs.csv spreadsheet refer to a fictional guitar factory, where the product parts would be a body, an arm, a headstock, etc. All those guitar parts go through many different machines and take different amounts of time in each one. The goal is to build a guitar as fast as possible.
