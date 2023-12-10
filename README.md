# deep-learning-challenge

Overview:
The purpose of analysis is to predict if a application for funding would be succesful from companys.With the use of machine learning we are trying to help alphabet soup classify and make better predictions.

Results:
-The target variable for the model is the IS_SUCCESSFUL column.
-The target features were application_type,affiliation,classification,use_case,organization,status,income,speical considerations, and ask_amt.
-Columns that were neither was NAME and EIN.
-
-I was not successful with hitting the target performance and was only able to peak at 74%.
-I attempted to not drop the NAME column however it would not allow my code to run in the other code blocks. I attempted to change the amount of EPOCHs but it didnt have a large effect but more so the pace and speed. I also added another layer and played around with different activations but had no success. Increasing and decreasing the cutoff values also did not help me reach my desired results.

Summary:
Overall im sure there was a way for me to better optimizatize the model however I just couldn't. It could potentially be because I missed one key thing to change or that I was changing too much at a time.

An alternative model that I would recommend is the Random Forest because its specialized in making classifications. 
