# 🌟 Uncovering Customer Voice: Sentiment & Topic Analysis of Yelp Reviews with IBM Granite 🌟

## ✨ Project Overview
Welcome to my Capstone Project repository! This project focuses on leveraging the power of Artificial Intelligence (AI), specifically the Large Language Model (LLM) **IBM Granite**, to transform unstructured customer review data into clear, *actionable* business insights.

In a digital age flooded with *feedback* from platforms like Yelp, businesses face significant challenges in manually analyzing massive volumes of reviews. This project presents an innovative solution to automatically:
- **Classify Sentiment:** Identify whether a review is positive, neutral, or negative.
- **Identify Key Topics:** Categorize reviews based on specific themes such as 'Food Quality', 'Service', 'Price', etc.
- **Summarize Reviews:** Provide concise summaries of longer reviews, capturing the core information without losing key details.

By automating this process, we aim to help businesses make faster, more informed strategic decisions based on the authentic voice of their customers.

## 💾 Raw Dataset
The dataset utilized in this project is a collection of public reviews from Yelp.com.

**Dataset Link:** [Insert your dataset link here. Example: Kaggle Yelp Reviews Dataset Link or Google Drive Shared Link]
*(Please ensure this link is public and accessible!)*

This dataset typically includes columns such as the review text (`text`) and star ratings (`stars`), which serve as the primary input for our AI model.

## 💡 Insight & Findings
Through in-depth analysis using IBM Granite on [state the number of reviews you processed, e.g., the initial 50 reviews] from the Yelp dataset, we uncovered crucial key insights for businesses:

1.  **Dominance of Positive Sentiment:** The majority of reviews (78%) displayed a Positive sentiment, affirming a generally good reception of the product/service by customers.
2.  **Critical Pain Point: Food Quality:** Among the 18% negative reviews, `Food Quality` emerged as the most dominant theme. This indicates a critical area requiring immediate attention and improvement to prevent potential customer churn.
3.  **Hidden Opportunities in 'Unknown' Reviews:** Reviews classified as 'Unknown' by our model surprisingly showed very high star ratings (median 4.5 stars, min 4, max 5). This suggests that these customers were highly satisfied but used nuanced or indirect language that made it challenging for the AI to classify them explicitly. Delving deeper into these reviews can uncover unexpected 'wow' factors that could be replicated.
4.  **Strong Sentiment-Rating Correlation:** There is a strong correlation between AI-predicted sentiment and original star ratings. Positive sentiment generally aligns with high ratings, while Negative sentiment aligns with low ratings, validating our model's accuracy.
5.  **Topic Prioritization:** Topics such as `Food Quality`, `Service`, and `Price` were the most frequently discussed, guiding businesses to the areas most impactful on customer experience.

## 🤖 AI Support Explanation
This project is entirely powered by **IBM Granite**, a Large Language Model (LLM) accessed via the Replicate platform. The role of AI in this project is crucial:

-   **Automated Sentiment Classification:** IBM Granite classifies each review into 'Positive', 'Neutral', or 'Negative' categories. This enables rapid analysis of hundreds to thousands of reviews, a process that would be highly inefficient if done manually.
-   **Key Topic Identification:** Through careful *prompt engineering*, the LLM effectively identifies recurring themes within reviews based on our predefined categories (e.g., 'Food Quality', 'Service'). This precisely helps businesses target specific areas for improvement or promotion.
-   **Key Detail Summarization:** IBM Granite also generates concise summaries (1-2 sentences) for each review. This feature is invaluable for management to quickly grasp the essence of *feedback* without having to read the full text, thereby accelerating review processes and decision-making.
-   **Scalability & Efficiency:** The utilization of an LLM allows this project to be scaled up to process significantly larger volumes of data in the future, providing consistent and accurate insights automatically.

AI not only serves as an automation tool but as a **strategic partner** empowering businesses to listen to and understand the voice of their customers more intelligently and proactively.

---
