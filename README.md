# Playground using transformer models / NLP projects
1. compare responses between vanilla ChatGPT (GPT 3.5 Turbo responses) vs RAG responses
   - Using GPT APIs, compared the vanilla version responses on the machine learning research around inventory management vs ones trained with 500 academic research papers searched with the "machine learning research around inventory management", scraped, and compiled into one PDF document to ease the loading process (see PDF_READER.ipynb).
   - Vanilla reposense:
   - "The most common application of machine learning for demand forecasting in supply chain management is predictive analytics. Predictive analytics uses machine learning algorithms to predict future customer demand, based on historical data. This is done by analyzing correlations between past customer demand and various factors such as seasonality, weather patterns, product mix, and customer demographics. Predictive analytics can provide an accurate forecast of future customer demand, allowing businesses to plan better and make more informed decisions.',"
   - Response after RAG; fed with 500 articles of academic papers on "machine learning on inventory management"
   - "The most common application of machine learning for demand forecasting in supply chain management is using AI applications to classify likely failure patterns and estimate machine conditions for faulty components. Another common application is using multiple classifier machine learning methodologies for predictive maintenance, allowing dynamic decision rules to be adopted for maintenance management. Additionally, machine learning models such as LSTM can be used for time series forecasting in supply chain management."

2. Conclusion:
     - you can tell that trained ones use more precise wordings around forecasting and modeling and are very specific on the particular use case scenarios for supply chain management.
    
3. Scripts
     - ChatGPT 3.5 Turbo Vanilla vs RAG Retrieval Comparison.ipynb
     - PDF_Reader.ipynb
