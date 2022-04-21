# IBM-Data-Science-Capstone-Project-SpaceX
A repository for Jupyter notebooks and relevant information for the IBM Data Science Professional Certification's final project focused on SpaceX. The challenge put forth by this course is to identify a machine learning model that can accurately predict whether a SpaceX stage 1 rocket will successfully be recovered.

The workflow for the project is as follows:
1) Extract data from a SpaceX API and suppliment it with relevant data from the Falcon 9 wikipedia page, which shows successful/unsuccessful launch data
2) Wrangle the data by filling in missing values with appropriate means (or eliminating data rows)
3) Visualize the data initially with matplotlib and seaborn
4) Plot successful launches on a map with Folium
5) Prepare machine learning models (LR, SVM, DecisionTree and k-nearest neighbor) to determine if any can identify a combination of factors which help predict successful stage 1 recoveries. 
