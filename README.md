outcomes -> 

![Screenshot (384)](https://github.com/raj075512/.ipynb_checkpoints/assets/91281709/5da9d64c-4fa2-4ed5-938c-57a94dbc2f70)


![Screenshot (385)](https://github.com/raj075512/.ipynb_checkpoints/assets/91281709/4d991b96-cda3-40b2-8c88-d35dda3c526a)

![Screenshot (386)](https://github.com/raj075512/.ipynb_checkpoints/assets/91281709/238a6f0a-bafe-489c-ab1e-83c1155c28df)

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
  1.9  **morning_trade** data from ( moneycontrol website )<br>
  1.10 **market_min** data from ( moneycontrol website )<br>
  1.11 **election2024** data from ( moneycontrol website )<br>
  1.12  adding the **random() dynamic generated depended target (y) variables** 

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

4. **apply NLP MODEL **<br><br>
   4.1 **logistic regression** calssification model<br>
       (a) using count vectorizer - get accuracy - 50%<br>
       (b) using tfidf vectorizer - get accuracy - 55%<br>
       <br> 
   4.1 **NAIVE - BAYES**  MODEL<br>
        both count vectorize as well as tfidf vectorizer



   

  
  
  
   
   
  
  
