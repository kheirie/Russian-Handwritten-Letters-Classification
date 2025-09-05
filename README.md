# Russian-Handwritten-Letters-Classification
This project was done for learning purpose. It focuses on classifying Russian handwritten letters written on different paper backgrounds. It is designed as both a Multi-Class and Multi-Label Classification problem.
- Multi-Class Classification: There are more than two possible classes — 33 unique letters and 4 different backgrounds.
- Multi-Label Classification: Each image has two labels to predict:
    - The letter (from а → я)
    - The background type (e.g., striped, gridded)

## Data 
The dataset can be found https://www.kaggle.com/olgabelitskaya/classification-of-handwritten-letters 

- Letter Symbols → Labels

``` а => 1, б => 2, в => 3, г => 4, д => 5, е => 6, ё => 7, ж => 8, з => 9,  
и => 10, й => 11, к => 12, л => 13, м => 14, н => 15, о => 16, п => 17, р => 18,  
с => 19, т => 20, у => 21, ф => 22, х => 23, ц => 24, ч => 25, ш => 26,  
щ => 27, ъ => 28, ы => 29, ь => 30, э => 31, ю => 32, я => 33 ```


- Backgrounds → Labels

``` striped       => 0  
gridded       => 1  
no background => 2  
graph paper   => 3 ```

