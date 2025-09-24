🎬 MovieLens 100K Recommender

Recommender system using User-based CF, Item-based CF, and SVD on the MovieLens 100K dataset. Evaluated with Precision@10 and RMSE.

🔑 Features

Load and preprocess MovieLens 100K

Leave-one-out evaluation

User-based CF

Item-based CF

Matrix Factorization (SVD)

Precision@10 and RMSE metrics

Save & reload SVD model

📂 Data

MovieLens 100K: 100,000 ratings

943 users, 1,682 movies

Automatically downloaded in the notebook

🧑‍💻 Workflow

Setup environment and imports

Download dataset

Load ratings and movies

Explore ratings and top movies

Create train/test split (leave-one-out)

Build User-based Collaborative Filtering

Build Item-based Collaborative Filtering

Apply SVD for Matrix Factorization

Evaluate models (Precision@10, RMSE)

Generate sample recommendations

Save SVD model

📊 Results (example)
Method	Precision@10	RMSE
User-based CF	~0.xx	–
Item-based CF	~0.xx	–
SVD (MF)	~0.xx	~0.xx
🚀 Sample Output

User-based recommendations: Top 10 unseen movies for a user
Item-based recommendations: Similar movies to user history
SVD recommendations: Latent factor–based personalized list

📌 Requirements

Python 3.9+

Numpy, Pandas, Scikit-learn, Scipy

Matplotlib, Seaborn, Joblib
