**OUTCOME**
![Screenshot (393)](https://github.com/raj075512/.ipynb_checkpoints/assets/91281709/a6abede6-159a-4156-8a79-f114c9590350)


**DATASET**
![Screenshot (394)](https://github.com/raj075512/.ipynb_checkpoints/assets/91281709/f39321d2-5243-4a36-a600-8b7a7dd2a1bc)





**PipeLines**- >>
1.data-formation of stock releted headlines for prediction of stock(nifty-50) via web scrapping .
<br> <br>

  1.1  **nifty** data from (  **timesofindia** - website )<br>
  1.2  **economy** data from ( **moneycontrol** website )<br>
  1.3  **mutualFund** data from ( moneycontrol website )<br>
  1.4  **ipo** data from ( moneycontrol website )<br>
  1.5  **personal_finance** data from ( moneycontrol website )<br>
  1.6  **business** data from ( moneycontrol website )<br>
  1.7  **indian_political** data from ( moneycontrol website )<br>
  1.8  **trends** data from ( moneycontrol website )<br>
  1.9 **election2024** data from ( moneycontrol website )<br>
  1.10  adding the **random() dynamic generated depended target (y) variables** 

2. **DATA-PREPROCESSING**  <br>
  
  2.1  make the new list of data_review -> merge the first row all sentence into it and store it, into data_review (list)
  <br>
  2.2  insert this into column and after intersrting it into column , preporcessing the whole data_review(final data) -> with <br> (a) lower_case <br>  (b) only aplebetical <br> (c) stopwords <br> (d) lemmatization
  <br>
  2.3 seperate depended varibles and independed variables 
  <br>

 
3. **feature -extration part**
   <br>
   3.1 train-test-split (4:1)  <br>
   3.2 vectorizer (count and tfidf)<br>

4. **apply NLP MODEL**<br><br>
   4.1 **logistic regression** calssification model<br>
       (a) using count vectorizer - get accuracy - 50%<br>
       (b) using tfidf vectorizer - get accuracy - 55%<br>
       
   4.2 **NAIVE - BAYES**  MODEL<br>
        both count vectorize as well as tfidf vectorizer<br>
   4.3 **PASSIVE AGGRESSIVE CLASSIFIER** (tfidf vectorizer)<br>
       accuracy with bi-gram-56 %<br>
       accuracy with tri gram -60% <br>
   4.4 **Random forest classifier**<br>
       got accuracy with 60% 
       

  
  
  
   
   
  
  
