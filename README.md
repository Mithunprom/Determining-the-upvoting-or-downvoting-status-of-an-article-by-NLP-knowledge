# Data-Science_codding_challenge
This Dataset is mainly The Dataset can be analyzed in different angels. First, we will see some tableau plot for data analysis and then a NLP problem description.

Tableau Data Analysis
The Tableau file is uploaded in this repository. First of all, we can have a view or idea regarding which authors have how many numbers of articles and how much upvotes they get for their articles in this dataset. Below a screenshot of tableau data analysis for these authors is given.

![](Sheet%201.png)

Here, we will have an idea regarding authors writing and their content. Also, We can see that the size of these circles defines which authors have larger writings and the color represents the number of upvotes of their writing. For example, Doremus-Jessup has most writings although he does not have maximum upvotes. Whereas, anutensi have most upvotes in his or her writings even though he or she was not one of the most written article holders over these years. From this, we can have an idea whenever we saw an article by an author. We will know if it will probably get an upvote or not.

Secondly, we can see over the year how these article numbers and upvotes are changing.

![](Sheet%202.png)



Although the number of articles is increasing each year compared to the previous years. The total number of upvotes received in the year 2015 is slightly highest. Maybe there are some writings style or contents or certain authors wrote more in that period which was more enticing than other periods.

Now whether an article is over_18 can be analyzed also. In the following portrayal, this is described.

![](Sheet%203.png)



Most of the articles are not over_18. Also, most upvotes articles are not over_18.

<p>Now it's time to connect the dots between these three plots. For this, I created a dashboard that incorporates all of three plots. One dashboard story is given below.
  
   ![](Capture1.JPG)
  
  Where we can see in the year 2015 which authors wrote the article and among these articles how many got upvotes from which authors or how many are over_18 from which authors. Thus through this dashboard, we can easily filter important information that we need. For example, in year 2015, most of the authors whi wrote in this period got upvotes. The total number of upvotes that's why high in this year compared to other years. </p>
  <p>  Also say, we want to analysis  Doremus-Jessup. He published articles fro years 2011-2016. He published most in 2015. Among all, his total upvotes are 277,001 where the total number of articles 1744 and all of them are not over_18. In the year 2015, he published most which are 47.5% of his total published article this year. Similarly, we can analyze the data from this created dashboard for each year or author, etc.</p>
  
  
  ![](Capture.JPG)

  <h> NLP problem</h>
 <p> If we inspect the data, we can create a text classification problem based on the article texts and whether an article gets upvotes or not. After reviewing the whole dataset, I concluded that it would be much fit if we classified the upvotes into two groups. Groups '0' where the articles get zero upvotes, group '1', where the article gets at least 1 upvote. For this, I am using a Neural network, which is renowned for the NLP problem and also has a greater advantage of this kind of situation. I use the combination of Dense, Convolution and LSTM layers and create a validation dataset that consists of 20% of the data. The loss and accuracy of both the training set and test sets are given below. Where we can see that the model loss converges to zero and accuracy converges to one. Both validation loss and accuracy gives high value. The following figure describes these values. The Whole architecture is built on Goggle Colab and it's given in this github repository('DataScience_coding_prob.ipynb'). </p>
  
  
