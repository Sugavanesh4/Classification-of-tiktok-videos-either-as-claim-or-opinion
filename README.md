# Clssification-of-tiktok-videos-either-as-claim-or-opinion
Overview:
     The aim of this project was to create a predictive model distinguishing between claim-based and opinion-based TikTok videos. After constructing and assessing both XGBoost and random forest models, the final random forest model consistently demonstrated high precision, recall, and f-1 scores. This model effectively identified crucial features for differentiating claims from opinion-based videos. Notably, user engagement metrics—such as views, likes, shares, and downloads—emerged as the most influential features in predicting the claim status of TikTok videos.
Modelling and evaluation:
     A random forest comprising 75 trees was used as the champion model to predict whether a video contained a claim or offered an opinion. The barplot below shows that in agreement with the prior EDA conducted, user engagement-related features such as views, likes, shares, downloads and comments were among the most important features in determining whether a video contains a claim.
Conclusion:
      The model effectively classified videos based on their claim status, with user engagement metrics emerging as the most predictive features. Initial data exploration revealed strong correlations between these engagement metrics and video claim status. Additionally, in-depth analysis involved statistical testing and regression modeling, detailed in the repository's notebooks. Before constructing the models, the 'video_transcription_text' feature, being text-based and not directly encodeable as a categorical feature, was excluded. However, there's potential to explore natural language processing techniques like the CountVectorizer algorithm to transform it into a usable feature, potentially enhancing the models' performance.






