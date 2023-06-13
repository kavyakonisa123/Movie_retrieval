Readme

•	Open the terminal 

•	Create a virtual environment using conda


Step 1: Check if conda is installed in your path.  

>>>conda -V

Step 2: Update the conda environment 

>>>conda update conda

Step 3: Set up the virtual environment 

>>>conda create -n <envname> python=x.x anaconda

Step 4: Activating the virtual environment

>>>conda activate <envname>

•	Place the templates, movienames.py and actor_names.py files in the virtual environment

•	Use the command to install all the required python modules

>>>pip install -r requirements. txt  
(Make sure it creates the requirements .txt file in the folder)

•	Run the flask application 

>>>Python movienames.py

•	Open the browser and paste the localhost address along with route decorator

http://127.0.0.1:5000/movie/1

1 = count  (you can change), these are the count of URLs the program has to crawl and scrape the data.
                       (This dynamically loads the HTML page with data retrieved) 


Similarly for actor_names.py
•	Run the flask application 

>>>Python actor_names.py

•	Open the browser and paste the localhost address along with the route decorator

http://127.0.0.1:5000/actor/1

1 = count  (you can change), these are the count of URLs the program has to crawl and scrape the data.
              (This dynamically loads the HTML page with data retrieved)



References:-

•	https://www.geeksforgeeks.org/set-up-virtual-environment-for-python-using-anaconda/
•	https://www.thepythoncode.com/article/extract-all-website-links-python
•	https://blog.jovian.ai/web-scraping-popular-movies-using-beautifulsoup-5bab0852fee4
•	https://towardsdatascience.com/web-scraping-basics-82f8b5acd45c
•	https://www.topcoder.com/thrive/articles/web-crawler-in-python



