# Project-Building-an-NLP-based-Doctor-Chatbot
Developed a doctor chatbot tailored for mental health conversations using the  NLP Mental Health Conversations dataset.  

Key Challenges:
Performance Comparison: Evaluated the effectiveness of LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) against the basic RNN (Recurrent Neural Network) model to understand which performs better.
Benchmarking: Compared the LSTM and GRU models with a benchmark Language Model (LLM) to gauge performance.

Approach:
Data Preparation: Cleaned and split the dataset into training and test sets. Tokenized and padded the conversations for model training.
Model Building: Constructed LSTM, GRU, and RNN models based on the dataset.
Architecture: Designed a clear architecture for each model, incorporating an embedding layer followed by the respective RNN layers.

Results:
LSTM and GRU outperformed the basic RNN model, demonstrating their efficacy in handling mental health conversations.
The benchmark Language Model (LLM) showcased superior performance compared to our custom LSTM and GRU models, highlighting the potential benefits of leveraging pre-trained models.
The project emphasizes the significance of model selection and the potential advantages of incorporating pre-trained language models for NLP applications in mental health.
