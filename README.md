# Konnexions Final Project

Roll no.: 21052080
### Spam and Ham e-mail Classifier
<u>In this project we will classify mails into ham and spam mails using machine learning algorithm with the assumption that words are independent of each other</u>

---

### Libraries

This project also includes nltk which is Natural Language ToolKit that includes the list of stopwords to be used to pre process the data

    import numpy as np
    import pandas as pd
    import nltk
    from nltk.corpus import stopwords
    import string
    from sklearn.feature_extraction.text import CountVectorizer
    from sklearn.feature_extraction.text import TfidfVectorizer
    from sklearn.model_selection import train_test_split