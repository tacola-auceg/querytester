# querytester
Query Testing Tool for Search Engines

How to run and test the code:

Download the file and extract it in to folder named QueryTesting_Tool. The folder can be opened as a project using Netbeans.

Main file: Query_Testing_Tool.java in the querytesting_tool package. 

When run opens a frame where the inputfile and outputfile are chosen to find the relevance of the results to the query.

Requirement: A text file (already.txt) with relevance of the result page to the query should be created previously to compare 
the results after modifications to the searching, ranking or index. The format in which the file should be created is shown 
below. Each line should represent each result pages relevance with the query.

1#தஞ்சை கோவில்#3/3/2013#http://www.trisakthi.com/ActionPages/Content.aspx?bid=553&rid=77#d19216881129265591533.txt#X

Input: A text file having the query and the resultpages in the format below is selected as input for relevance checking by 
clicking the open button in the frame.

Output: The ouput of the querytesting is written to the file which is chosen using the save button in the frame.

Interface: Has buttons open to select the input file and save button to select the output file. The query testing button is 
used to find the relevance of the new result pages to the query from the already tagged result pages.

Example: Input : 

1#தஞ்சை கோவில்#3/3/2013#http://www.trisakthi.com/ActionPages/Content.aspx?bid=553&rid=77#d19216881129265591533.txt
1#தஞ்சை கோவில்#3/3/2013#http://labbaikudikadu.com/pages/travel_detail.aspx?id=BAA29599-4753-4189-9209-887DC47A15C3#d19216881129251042949.txt
1#தஞ்சை கோவில்#3/3/2013#http://www.labbaikudikadu.com/pages/travel_detail.aspx?id=3C56274F-31B6-4163-8058-1EC453739527#d19216881129252136521.txt
1#தஞ்சை கோவில்#3/3/2013#http://labbaikudikadu.com/pages/travel_detail.aspx?id=3C56274F-31B6-4163-8058-1EC453739527#d1921688196241621396.txt
1#தஞ்சை கோவில்#3/3/2013#http://tamil.webdunia.com/newsworld/news/tnnews/0807/15/1080715005_1.htm#d19216881322423192996.txt
1#தஞ்சை கோவில்#3/3/2013#http://tamil.webdunia.com/newsworld/news/tnnews/0807/15/1080715005_1#d19216881322423192996.txt

Output :

1#தஞ்சை கோவில்#3/3/2013#http://www.trisakthi.com/ActionPages/Content.aspx?bid=553&rid=77#d19216881129265591533.txt#X
1#தஞ்சை கோவில்#3/3/2013#http://labbaikudikadu.com/pages/travel_detail.aspx?id=BAA29599-4753-4189-9209-887DC47A15C3#d19216881129251042949.txt#W
1#தஞ்சை கோவில்#3/3/2013#http://www.labbaikudikadu.com/pages/travel_detail.aspx?id=3C56274F-31B6-4163-8058-1EC453739527#d19216881129252136521.txt#P
1#தஞ்சை கோவில்#3/3/2013#http://labbaikudikadu.com/pages/travel_detail.aspx?id=3C56274F-31B6-4163-8058-1EC453739527#d1921688196241621396.txt#P
1#தஞ்சை கோவில்#3/3/2013#http://tamil.webdunia.com/newsworld/news/tnnews/0807/15/1080715005_1.htm#d19216881322423192996.txt#P
1#தஞ்சை கோவில்#3/3/2013#http://tamil.webdunia.com/newsworld/news/tnnews/0807/15/1080715005_1#d19216881322423192996.txt
