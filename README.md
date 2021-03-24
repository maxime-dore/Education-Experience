# Education-Experience
This repository sums up all my working projects realised during my studies at INSA and Toulouse Business School.

## <a href="http://www.insa-toulouse.fr/" ><img src="http://www.math.univ-toulouse.fr/~besse/Wikistat/Images/Logo_INSAvilletoulouse-RVB.png" style="float:left; max-width: 80px; display: inline" alt="INSA"/> |  [*Applied mathematics*](http://www.math.insa-toulouse.fr/fr/index.html), [`Data Science`](http://www.math.insa-toulouse.fr/fr/enseignement.html) 

# Artificial Intelligence Frameworks

This course follows the [Machine Learning](https://github.com/wikistat/Apprentissage) and the [High Dimensional & Deep Learning](https://github.com/wikistat/High-Dimensional-Deep-Learning) courses.
 In theses courses, you have acquired knowledge in machine and deep learning algoritms and their application on various type of data. This knowledge is primordial to become a DataScientist. 

This course has three main objectives. You will 

1. learn how to apply efficiently these algorithms using
    * Cloud computing with [Google Cloud](https://cloud.google.com/gcp/?utm_source=google&utm_medium=cpc&utm_campaign=emea-fr-all-en-dr-bkws-all-all-trial-e-gcp-1003963&utm_content=text-ad-none-any-DEV_c-CRE_167374210213-ADGP_Hybrid%20%7C%20AW%20SEM%20%7C%20BKWS%20~%20EXA_1:1_FR_EN_General_Cloud_TOP_google%20cloud%20platform-KWID_43700016295756942-kwd-26415313501-userloc_9055236&utm_term=KW_google%20cloud%20platform-ST_google%20cloud%20platform&ds_rl=1242853&ds_rl=1245734&ds_rl=1245734&gclid=EAIaIQobChMIvaa_9OmL4gIVFeaaCh3jnQIfEAAYASAAEgJyp_D_BwE),
    * Container with [Docker](https://www.docker.com),

2. discover new field of artificial intelligence applied on (real) datasets that require specific algorithms:
    * **Text**.
        * <ins>Algorithms</ins>: Text processing, Vectorizer, Words Embedding, RNN
        * *Libraries :  [Nltk](https://www.nltk.org/), [Scikit-Learn](https://www.tensorflow.org/), [Gensim](https://gym.openai.com/)*
    * **Video Game**
        * <ins>Algorithms</ins>: Reinforcement learning, (Policy Gradient algorithm, Q-Learning, Deep Q-learning)
        * *Libraries :  [AI Gym](https://gym.openai.com/), [Tensorflow](https://www.tensorflow.org/).
    * **Movies Notations**
        * <ins>Algorithms</ins>: Recommendation system, (User/User and Item/Item filters, NMF, Neural recomendation system)
        * *Libraries :  [Surprise](https://surprise.readthedocs.io/en/stable/index.html), [Tensorflow](https://www.tensorflow.org/).

3. how to efficiently share reproducible code. 
    * Build a Github repository.



## Knowledge requirements

- [R Tutorial](https://github.com/wikistat/Intro-R)
- [Python Tutorial](https://github.com/wikistat/Intro-Python)
- [Elementary statistic tools](https://github.com/wikistat/StatElem)
- [Data Exploration and Clustering](https://github.com/wikistat/Exploration). 
- [Machine Learning](https://github.com/wikistat/Apprentissage)
- [High Dimensional & Deep Learning](https://github.com/wikistat/High-Dimensional-Deep-Learning)




Course introduction + Github Reminder: [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Course_Introduction.pdf)/[Video](https://youtu.be/PMwIehZd8Yg) <br>


- **Session 1 - 02-11-20**
   - **Text**: Text Cleaning + Text Vectorization
        * [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Text_Cleaning_Vectorisation.pdf) / [TP](https://github.com/wikistat/AI-Frameworks/blob/master/Text/1_cleaning_vectorization.ipynb) / [Video](https://www.youtube.com/watch?v=z1svuMQ5iVU)
   - **Text**: Words Embedding.
        * [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Text_Word_Embedding.pdf) / [TP](https://github.com/wikistat/AI-Frameworks/blob/master/Text/2_words_embedding.ipynb) / [Video](https://youtu.be/mB7Q-LC_vFU)
- **Session 2 - 16-11-20**
   - **Text**: Recurrent Network
        * [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Text_Recurent_Neural_Network.pdf) / [TP](https://github.com/wikistat/AI-Frameworks/blob/master/Text/3_recurrent_neural_network.ipynb) / [Video](https://youtu.be/l4_52JCPupI)
   - **Development for Data Scientist**: Python environment + Github Repo + Python Script.
        * [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Code_Development_Python.pdf) / [TP](https://github.com/wikistat/AI-Frameworks/tree/master/CodeDevelopment/TP.pdf) / [Video](https://youtu.be/gZLeTHQzloE)
- **Session 3 - 30-11-20**
   - **Development for Data Scientist**: Introduction to Google Cloud Computing.
        * [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Code_Development_Google_Cloud.pdf) / [TP](https://github.com/wikistat/AI-Frameworks/tree/master/CodeDevelopment/TP.pdf) / [Video](https://youtu.be/FOsGsMrDJE8)
   - **Development for Data Scientist**: Docker
        * [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Code_Development_Docker.pdf) / [TP](https://github.com/wikistat/AI-Frameworks/tree/master/CodeDevelopment/TP.pdf) / [Video](https://youtu.be/loMf5bFyzY4)
- **Session 4 - 07-12-20**
   * Introduction to deep Reinforcement learning: Deep Q-learning 
       - [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Introduction_DRL_DeepQLearning.pdf) / [Video](https://youtu.be/C6NlqWIHJk8)
       - **Q Learning reminder**: [TP](https://github.com/wikistat/AI-Frameworks/tree/master/IntroductionDeepReinforcementLearning/Q_Learning.ipynb) 
       - **Deep Q Learning on cartpole**: [TP](https://github.com/wikistat/AI-Frameworks/tree/master/IntroductionDeepReinforcementLearning/Deep_Q_Learning_CartPole.ipynb) 
       - **Deep Q Learning on Gridworld**: [TP](https://github.com/wikistat/AI-Frameworks/tree/master/IntroductionDeepReinforcementLearning/Deep_Q_Learning_GridWorld.ipynb) 

- **Session 5 14-12-20**
    - **Introduction to deep Reinforcement learning**: PG Gradient
        * [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Introduction_DRL_PG.pdf) / [TP](https://github.com/wikistat/AI-Frameworks/tree/master/IntroductionDeepReinforcementLearning/Policy_Gradient.ipynb) / [Video](https://www.youtube.com/watch?v=xadl6kfM5Bk)  
    - **Recommendation System**. 
        * [Slides](https://github.com/wikistat/AI-Frameworks/blob/master/slides/Recommendation_System.pdf) / [TP1](https://github.com/wikistat/AI-Frameworks/tree/master/RecomendationSystem/surprise.ipynb) & [TP2](https://github.com/wikistat/AI-Frameworks/tree/master/RecomendationSystem/tensorflow.ipynb) / [Video](https://youtu.be/VIUq9PP6h-w)
- **Session 6 04-01-20**
   - Free time on project.






 
 ## Technical requirements. 
 
 All the libraries required for these modules are listed in the `requirements.txt` 
 
 To build a functional environment in pandas execute the following lines:
 
 ```
conda create -n AIF python=3.8
conda activate AIF
pip install -r requirements.txt 
jupyter labextension install jupyterlab-plotly@4.12.0
```
