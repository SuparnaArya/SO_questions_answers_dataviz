# SO_questions_answers

The purpose of this project was to explore different metrics for Stack Overflow questions and their answers from January 2021 to June 2021.Initial data was pulled from Bigquery public stackoverflow dataset.Data was collected for two tags-python and javascript. Python and Javascript Q&A data is stored in "python-jan'21-jun'21.csv" and "javascript-jan'21-jun'21.csv" files.Please download them from [ this Google drive link ](https://drive.google.com/drive/folders/1k-Ri47jTRi2RF7CkpsSGvK4iYo5rGI7x?usp=sharing). 2 CSV files were generated from them with 5 metrics for Python and Javascript tags named as "python_metrics.csv" and "javascript_metrics.csv". The five metrics are:

1. **View count :** How many times a question was viewd.This indicates how popular is the question
2. **Score :** Sum of all upvotes and downvotes it received
3. **Answer count :** How many answers were given for the question. Higher number sometimes indicate multiple ways to solve a problem.
4. **Comment count :** Comments associated with the question.They provide additional info and sometime ask the asker to elaborate the question.
5. **First response time :** Earliest answering time for a question.This indicates how responsive the community is.

## Takeways from the analysis

![image](https://user-images.githubusercontent.com/50947232/145873551-cd88566c-a452-4026-a56d-b938f222480a.png)
- Mean views and average score were higher for python but javascript received slightly more answers in average and also higher comments.This may mean that the questions associated with pythons are more self explanatory so they had less comments. Also the average first response time were higher for python.It may indicate that python questions take slightly higher time to get solved.

![image](https://user-images.githubusercontent.com/50947232/145874467-119ed26f-20ce-491b-b2f5-e22f8dfa031c.png)
- There's almost no variation for the two tags for their respective minimum values in metrics expect for a python question received the lowest score.

![image](https://user-images.githubusercontent.com/50947232/145874776-e3d84fa7-7cc6-4b62-a734-bab847d0f396.png)
- Considerable difference is between the maximum views that a question received for python and javascript.There is a highly popular python question that supassed the javascript question with highest views by a great margin.Also the highest time taken to respond to a question belonged to python.

![image](https://user-images.githubusercontent.com/50947232/145875229-7d08e1a1-f43a-4645-a413-6597ef7a701f.png)
- Python has greater total views count,total answers and total comments as a whole.Which is due to the number of total questions asked in this time frame for the two tags,where python stands higher.
- Python also has higher number of unique askers and answerers. A python question answerer answered 139007/34675=4 answers on average where a javascript answerer answered 71087/32864=2.1 answers on average.
- 
![image](https://user-images.githubusercontent.com/50947232/145875592-a2e9bed8-0bd5-45d1-8961-53ca75ac412e.png)

![image](https://user-images.githubusercontent.com/50947232/145876164-2fa5b16e-417d-44c6-88d4-44d264eaa672.png)
- The figure depicts the number of unique users as askers and answeres for both tags. This shows a small fraction but considerable fractions of developers is working on both python and javascript in 6 months period and some keep active knowledge on both languages.

![image](https://user-images.githubusercontent.com/50947232/145876795-0791290e-b8e6-4a25-babc-21fa9eebef05.png) ![image](https://user-images.githubusercontent.com/50947232/145876927-7e694c00-daf7-4f3c-8269-b35d7956c7f5.png)

- The graphs show the trends of asking questions and answers over 6 month period from January'21 to June'21. The patterns are similar for both python and javascript for questions and answers. However since the project only looks at questions that have received answers, there might be questions which has remained answered by the platform. Overall,python community seems more engaged in knowledge sharing than javascript community in the timeframe studied.

