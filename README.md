# AI-Driven-Cancer-EHR-Analysis-Information-Retrieval-Structured-Data-Extraction
# EHR Treatment Retrieval
AI-Driven Cancer EHR Analysis: Information Retrieval &amp; Structured Data 

## Overview
This project focuses on extracting and retrieving relevant treatment records from Electronic Health Records (EHR) data. It processes multiple datasets, answers specific queries regarding patient treatments, and evaluates the system's performance by calculating and visualizing similarity scores. The performance of the retrieval system is assessed by plotting these scores for each query across different datasets.

## Features
- **Data Preprocessing**: Cleans and processes EHR data by removing sensitive patient information (PHI) and extracting relevant treatment sections.
- **Query-based Retrieval**: Retrieves the most relevant treatment records based on predefined queries, using a sentence-transformer model to encode the data.
- **Performance Evaluation**: Visualizes the performance of the system by plotting the top similarity scores for each query across different datasets.
- **Radiation Treatment Detection**: Identifies radiation-related treatments from the EHR data using predefined patterns.

## Dataset
The project works with datasets in JSON format, where each dataset contains patient treatment records. Example files include:
- `1.json`
- `2.json`
- `3.json`

Ensure the datasets follow the structure required by the system for proper processing and query retrieval.

## How to Use
1. **Preprocessing**: The system processes the raw EHR data, removes sensitive information, and extracts relevant treatment records based on the queries provided.
2. **Query Matching**: A list of queries can be input into the system, and the most relevant treatment records will be retrieved for each query.
3. **Performance Visualization**: After retrieving the treatment records, the system plots a graph comparing the similarity scores across different datasets for each query.

## Results
After running the queries, the system provides the top similarity scores for each query and dataset. These results are visualized in a graph, showing how well the system performs across different queries and datasets.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- **Sentence-Transformers**: For providing the pre-trained model used for text encoding and comparison.
- **Scikit-learn**: For implementing cosine similarity to compare query and dataset records.
- **Matplotlib**: For generating graphs to visualize the performance evaluation across queries and datasets.

