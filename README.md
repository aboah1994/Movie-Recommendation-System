# Movie-Recommendation-System
A simple NLP algorithm for recommending movies

Summary: In this project I developed a simple movie recommendation system, that returns the top 10 movies base on a given movie title.

# Process
1. Load csv/text files containing your movie titles and the plot/overview of each movie
2. Merge the two csvfiles based on id and remove all rows with nan's
3. Import TfidfVectorizer (Term frequency Inverse Document frequency) module from sklearn
4. Create tfv using TfidfVectorizer and apply the fit_transform to obtain the tfv_matrix
5. Compute the Sigmoid kernel scores

