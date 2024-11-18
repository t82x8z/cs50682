java c
HUDM 5026 - Introduction to Data Analysis and Graphics in R
HW 3 – Logical Operators and Missing Values
Instructions.
•  Turn in an R script. ﬁle.
•  Feel free to discuss problems with classmates.
•  All work you submit must be your own.
•  If you use any sources, including large language models like chatgpt, cite them with a note and explain your code.For this HW you will work with the text from the famous novel, Alice’s Adventures in Wonderland, by Lewis Carroll.  Navigate to Project Gutenberg to view a text ﬁle version of the novel here https://www.gutenberg.org/files/11/11-0.txt.  Read the ﬁle into R using read_file() from package readr, which is part of the tidyverse.
aiw  <-  read_file(file  =  "https://www. gutenberg. org/files/11/11-0. txt ")
Task 1  How many characters  does  aiw contain?  Is  it  a vector?  What is the length of the vector?
Task 2  Examine the ﬁrst 3000 characters  of the text of the  book with str_sub() .Task 3  Note that when imported, the text ﬁle  brought along some formatting in the way of "\n"  and  "\r"  strings.   Find  and replace  these  using  gsub()  or str_replace_all()  and save the output as aiw2.Task 4  Clean  up  whitespace  by deleti代 写HUDM 5026 - Introduction to Data Analysis and Graphics in R HW 3Processing
代做程序编程语言ng whitespace  at the  beginning/end of strings  and re- placing  multiple  whitespaces  with  a  single  whitespace.   Hint:   see  str_squish() .   Save  as aiw2.
Task 5  Project  Gutenberg  has  added  some  text  at  the  beginning  and  end.    Find  the  true beginning and ending of the text and save  only the book text.  Save this  as  aiw2.Task 6  Note that aiw2 is a single long character string.  We would like to separate the words so that each is it’s own element of a character vector.  Use  strsplit or str_split() to do that and rename the result as aiw3.  This will produce  output in a list,  but we want a vector, so use unlist() on aiw3 to turn it into  a long character vector;  again, save the output as aiw3.
Task 7  What proportion of words in the book contain at least one uppercase letter? Task 8  What proportion  of words  in the book use some form. of punctuation?
Task 9  Create  a barplot of word frequency for the  top  20 most frequent words.
Task 10  This  bonus  question is not required for full  credit  but worth a couple of extra points. Run a sentiment analysis on the cleaned text.  Describe the ﬁndings.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
