# INF2178-Project
UT INF2178 Experimental Design for Data Science

--------
1. Clone repository using git clone
2. Go to the repository's folder
3. Create the environment:
```
conda env create --force -f environment.yml
```
4. Activate the environment:
```
activate inf2178-project
```
5. Run Jupyter notebook:
```
jupyter notebook
```

### Kaggle link:  
https://www.kaggle.com/petersunga/google-amazon-facebook-employee-reviews  

### Context:  
Over 67k employee reviews for Google, Amazon, Facebook, Apple, and Microsoft

### Content:  
This dataset contains employee reviews separated into the following categories:

Index: index

Company: Company name

Location : This dataset is global, as such it may include the country's name in parenthesis [i.e "Toronto, ON(Canada)"]. However, if the location is in the USA then it will only include the city and state[i.e "Los Angeles, CA" ]  

Date Posted: in the following format MM DD, YYYY  

Job-Title: This string will also include whether the reviewer is a 'Current' or 'Former' Employee at the time of the 
review  

Summary: Short summary of employee review  

Pros: Pros  

Cons: Cons  

Overall Rating: 1-5  

Work/Life Balance Rating: 1-5  

Culture and Values Rating: 1-5  

Career Opportunities Rating: 1-5  

Comp & Benefits Rating: 1-5  

Senior Management Rating: 1-5

Helpful Review Count: A count of how many people found the review to be helpful  
Link to Review : This will provide you with a direct link to the page that contains the review. However it is likely that this link will be outdated  

NOTE: 'none' is placed in all cells where no data value was found. 
