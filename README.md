**Behavioural Data Science Toolbox**  
**Pressure Cooker: het Epos**

**Group members:**

- Isabella Braune 
- Danielius Rimas
- Kassandra Vrouli 

**Research question:** Which aspects of early years education should the school
prioritise for improvement in order to maximise pupils’ development during
the kindergarten years and their success throughout the rest of their school
career?  

**Sub-question 1**: Extended time in kindergarten What effects does spending a
longer period in kindergarten have on pupils’ cognitive, social-emotional and
executive development, and on their functioning in Years 3 and 4?  

**Sub-question 2**: Teaching focus aligned with Years 3 and 4
What effects does a teaching focus on learning objectives aligned with Years 3
and 4 have on pupils’ academic achievement and subsequent educational pathways?


## About this project

Het Epos Primary School is an educational organisation founded in 2019 by the
philanthropic Stichting De Verre Bergen. The school opened in Rotterdam-Zuid in
2020 and was founded on the conviction that differences in learning outcomes
between schools are related not only to pupils’ backgrounds, but also to the
quality of education. The school aspires to be among the best schools in 
Rotterdam, with high expectations for language and mathematics as well as broad
attention to children’s development into young adulthood. 

## Cloning this project

To get a copy of this project on your own computer, as an RStudio project:

1. On this repository's GitHub page, click the green `<> Code` button,
   choose **HTTPS**, and copy the URL.
2. In RStudio, make sure no project is open (top right: `Project: (None)`).
3. Go to `File` > `New Project` > `Version Control` > `Git`, paste the URL
   into `Repository URL`, choose where the project should live on your computer,
   and click `Create Project`.


## Reproducing this project

1. Open the project in RStudio (double-click its `.Rproj` file, or clone it as
   described above).
2. Within the same folder where this project lives, create a folder called data
   This file has been included in .gitignore so will not be uploaded.
3. Download the datafiles provided to us by Epos in this folder. 
4. Run `00-packages.R` to install and load the packages this project uses.
5. Knit `Data_Transformations.Rmd` (the final report). Knitting runs the script above
   for you.
If the steps described above have all been carried out the html should render 
and all the data transformations in the .rmd file should run without errors. 

