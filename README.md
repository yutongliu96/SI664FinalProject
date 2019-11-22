# SI664FinalProject 

The team plans to do the project which bases on the dataset from
Kaggle(https://www.kaggle.com/karangadiya/fifa19). This dataset has aggregate 89
columns that descript details in FIFA2019. The team plans to choose suitable
columns that can meet the one to many and many to many relationships to use.
And for the website interactive part, we will offer the users not only valid data but
also interactive visualization which can help them understand the FIFA2019 more
detailed.
The website will offer following function:
1. Data view
2. Data edit
3. Data interactive visualization
4. Basic functions (such as Login and Log out)

## Home page, Login and Register
We will put login and register on the same home page after entering our website.
![the beginning page](https://github.com/yutongliu96/SI664FinalProject/blob/master/UI/login.JPG)

## Data Visualization Page
The data visualization page will provide some detailed visualization for interactions about dataset such as average age for different player positions.
![DV page](https://github.com/yutongliu96/SI664FinalProject/blob/master/UI/data_visualization.JPG)

## Data View Page
Data view page is used to view the data details.
![data view page](https://github.com/yutongliu96/SI664FinalProject/blob/master/UI/data_view.JPG)

## Logout Page
After clicking the logout button, there will be a independent page for logout information.
![log out page](https://github.com/yutongliu96/SI664FinalProject/blob/master/UI/logout.JPG)

## Data Model
The database contains 7 tables, which are Player, Club, Nationality, Overall Score, Potential Score, Position, and Age. 2 many to many relationships are created, which are between Club and Nationality, Nationality and Overall Score. This is achieved by using Player table as a big junction table. Bsides, Club also have one to many relationship with Player, Overall Score and Potential Score. In this way we can clearly see the competition level of a club.  The other tables all have one to many relationship with Player.
![data model](https://github.com/yutongliu96/SI664FinalProject/blob/master/statics/Data_Model.png)
