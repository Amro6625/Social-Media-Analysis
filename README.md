

## Introduction:

The project focuses on understanding community sentiments toward Humberside Fire and Rescue through social media, utilizing sentiment analysis and risk detection. While sentiment analysis has been extensively explored, this research innovates by applying various deep learning models. The introduction highlights the significance of leveraging advancements in AI to anticipate and manage potential risks, enhancing community safety.



## Methodology:

Data collection involved Twitter API for @HumbersideFire and #HumbersideFire from 2019 to 2023, resulting in 5,527 tweets. Additional Kaggle data with 16,130 labeled tweets was utilized. Key contributors and official accounts were excluded for unbiased sentiment analysis. Preprocessing involved removing mentions, hashtags, URLs, and standardizing text. Various models, including RoBERTa, BiLSTM, and XLNET, were employed for sentiment analysis and risk detection, emphasizing a robust and accurate analysis.



## Results:

Sentiment analysis, utilizing the RoBERTa pretrained Cardiff model, revealed positive community sentiments (56.4%), with the majority expressing gratitude or support. Risk detection using RoBERTa Base exhibited 93% accuracy, outperforming XLNET and BiLSTM. Temporal sentiment trends showed no direct correlation with events, except during the River Aire flooding. Custom text inputs validated RoBERTa Base's effectiveness in identifying potential risks on social media.



## Discussion:

The RoBERTa pretrained sentiment model displayed higher accuracy in predicting tweets than the emotions model. Positive tweets expressed gratitude, neutrals included public announcements, and negatives often reported incidents. Sentiment trends did not directly correlate with events, except during the River Aire flooding. The RoBERTa Base model's superior performance in risk detection highlights its potential for proactive emergency response, contributing to improved community safety.



## Conclusion:

The examination of community attitudes underscored the significance of advanced natural language processing models, with the RoBERTa Base model demonstrating superior accuracy. The community highly values Humberside Fire and Rescue, as evidenced by mostly positive sentiments. The success of the risk detection model, particularly RoBERTa Base, highlights its potential for proactive emergency response and improved community safety. Ongoing refinement and exploration are recommended for adapting to changing dynamics and enhancing overall accuracy.






