**STRUCTURED INFORMATION RETRIEVAL USING LLMs FOR ACADEMIC RESEARCH**


**Overview**

This project demonstrates the use of a Bi-LSTM (Bidirectional Long Short-Term Memory) and fine-tuned BERT (Bidirectional Encoder Representations from Transformers) model for entity extraction from text documents. Both models are leveraged to perform Named Entity Recognition (NER) tasks on textual data, providing structured information by identifying entities such as names, dates, and other specific terms within the text. This approach is particularly useful for academic research, where precise and accurate information retrieval is crucial.

**Project Structure**
Data Processing: The code preprocesses text data to prepare it for entity extraction using both Bi-LSTM and BERT models. This involves tokenization, encoding, and any necessary data transformations.

**Model Implementation:**

Bi-LSTM Model: The Bi-LSTM model is implemented to capture sequential dependencies in the data, making it effective for tasks that require understanding the context before and after a given word.
BERT Model: A fine-tuned BERT model is also utilized for entity extraction, leveraging its deep contextual understanding to improve accuracy.
Entity Extraction: The core function of the code involves using both the Bi-LSTM and BERT models to extract entities from the input text. The results from both models are displayed, with entities labeled according to their specific type.

**Requirements**
Python 3.7+
Transformers Library (Hugging Face)
PyTorch
Pandas
NumPy
**How to Run**
Setup the environment: Ensure that all the required libraries are installed. You can use the provided requirements.txt to install dependencies.
pip install -r requirements.txt
Execute the notebook: Run the Jupyter notebook to perform the entity extraction process on your text data using both the Bi-LSTM and BERT models.

**Review Outputs:** The extracted entities will be displayed in the notebook, with labels corresponding to the specific entity types identified by each model.

**Results**
The results section of the notebook displays the extracted entities from the processed text using both the Bi-LSTM and BERT models. This structured information is invaluable for further analysis or as input to other models or systems, particularly in the context of academic research.

**Conclusion**
This project illustrates the effectiveness of combining Bi-LSTM and BERT models for entity extraction tasks. The integration of these models provides a robust tool for NLP applications, capable of accurately identifying and labeling entities within a text. The approach is particularly useful in domains like information retrieval and document analysis, making it a valuable asset for academic research.
