# Start-up-AI-product
<h1><center> “Good Dinner AI”</center></h1>
<h3>Use case</h3>
“As a user of Good Dinner, I can:

* post reviews in the form of comments.
* post photos taken in the restaurant.”

“As Good Dinner, I wish to:

* Detect the topics of dissatisfaction in the comments posted on the platform.
* Automatically label photos posted on the platform. For example, identifying photos related to food or decor inside or outside the restaurant.” 

<h3>Scope of the project</h3>

Preliminary study of feature “Detect the topics of dissatisfaction” and “Automatically label posted photos”

<h3>Dataset and Data Collection</h3>

* Problem: Insufficient data available on the Good Dinner platform.
* Solution: Use an existing dataset.

        * Link to the dataset: https://www.yelp.com/dataset (Contains general information (e.g., type of cuisine) and consumer reviews of different restaurants) 
        * To fetch new data use the yelp API

<h3> Methodology and process</h3>

* analyze the comments in order to detect topics of dissatisfaction:
>> * pre-process text data
>> * use dimension reduction techniques
>> * visualize high-dimensional data
* analyze photos in order to determine their categories 
>> * pre-process images
>> * use dimension reduction techniques
>> * visualize high-dimensional data
* collect sample collection (approximately 200 restaurants) of data via the Yelp API:
>> * retrieve only the necessary fields
>> * store the results in a usable file format (e.g., csv)
<h3>Tools</h3>
	
* Python and specialized NLP/CV libraries
* Jupyter Notebook and Voilà package