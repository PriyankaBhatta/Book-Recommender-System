# Book-Recommender-System

I built a book recommender system using collaborative filtering approach. I started by cleaning and modeling the data in Jupyter Notebook. Once the model was trained, I exported it using pickle and saved it in my VS Code project folder. To provide an interactive interface, I used Flask to develop a web application. The application has two main routes: the home page and the recommendation page. On the home page, users can see the top 50 recommended books. In the recommendation page, users can enter a book name and click the 'recommend' button. The Flask route for the recommendation page receives the user's input, loads the pre-trained model from the pickle file, and generates the top 5 book recommendations based on collaborative filtering. The recommendations are then displayed on the page. I used HTML templates to render the recommendations and ensure a user-friendly interface.

The datasets I used for this project are from kaggle. 
Link to the datasets: https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

The landing page where the top 50 books with most amount of ratings is show.
![image](https://github.com/PriyankaBhatta/Book-Recommender-System/assets/109200742/97190afa-578e-4f76-8a74-d27eacc66b96)

After clicking on recommend option on header, the user will be directed to recommend page.
![image](https://github.com/PriyankaBhatta/Book-Recommender-System/assets/109200742/346f1892-2da4-46ea-99ab-5a5c9e409ed4)

Then, when the user enters a book name and clicks on recommend button, top 5 similar books will be generated using collaborative filtering based approach.
![image](https://github.com/PriyankaBhatta/Book-Recommender-System/assets/109200742/b0643d44-d7ba-4d24-a52b-ac995f4f8b45)



