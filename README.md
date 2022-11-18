# Paper Analysis -  Profiling, Analysis, Cleaning, Preparation and Modeling of text data

This repo consist in a simple Data Cleaning Pipeline using basic tools in order to Analyse a set of different papers related to "Digital Twin" tecnology. The main goal of the project was to clean the data (obtained by hand) analyse the main keywords and produce an algorithm that would identify how closelly related each paper is with one another, in order to help the researchers of an Digital Twin project at Politecnico di Milano to select the best papers to be used. 

This is not a deployed application, and it is divided in two notebooks:
- `eda.ipynb`: Profiling, Analysis and Data Cleaning
- `modeling.ipynb`: Modeling of the features and strings to create a similarity detection algorithm between papers

The project mainly involves:
- Basics concepts of profiling with Pandas and Pandas_profiling (html files generated can also be found in the repo) 
- Data Cleaning and Transformation with Pandas 
- String Analysis with Bar plots and Wordclouds
- String Similarity with CountVectorizer and Cosine Similarity
