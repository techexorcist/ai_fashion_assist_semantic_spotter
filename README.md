
# AAI FASHION ASISTS (Semantic Spotter) - Myntra

## Description
Create a generative search system capable of searching a plethora of product descriptions to find and recommend appropriate choices against a user query. You may use this Myntra dataset on Kaggle to build such a system.

On modern e-commerce platforms like Myntra, users are often presented with an overwhelming number of product descriptions, making it difficult to efficiently locate relevant items. Typically, users have specific queries or requirements, such as seeking products with particular features, styles, or brands. The main challenge lies in creating a search system that can comprehend natural language queries, sift through extensive product descriptions, and deliver precise and relevant product recommendations.

## Goals
### Develop a Sophisticated Search System: Create a search engine that understands and accurately interprets natural language queries, delivering relevant and precise product recommendations.
### Ensure User Experience: Design a system that queries data while providing a fast, intuitive, and personalized search experience.

## Key Challenges:
### Natural Language Understanding: The system must accurately comprehend and interpret user queries expressed in natural language.
### Data Integration: The system needs to integrate various data sources and manage comprehensive product descriptions.
### Relevance and Accuracy: The system must produce search results that are both relevant to the user’s query and precise.
### Scalability: The system should handle an increasing number of products and queries without a drop in performance.
### User Experience: Ensuring that the search interface is intuitive and user-friendly, facilitating an easy and efficient search process.
### Real-Time Processing: The system should provide fast and real-time search results, enhancing user satisfaction and engagement.
### Personalization: The system must incorporate user preferences and behavior to provide personalized search results and recommendations.
### Multilingual Support: The system should support multiple languages to cater to a diverse user base.
### Security and Privacy: Ensuring that user data is protected and privacy is maintained throughout the search process.
### daptability: The system must adapt to changing trends, new products, and user behavior over time to maintain its effectiveness.

## Technical Specifications
### Libraries and Tools:
#### Data Processing: numpy, pandas
#### Visualization: matplotlib, seaborn
#### NLP and AI: openai, sentence_transformers, langchain
#### Data Management: chromadb, FAISS, Chroma
#### Web Interface: gradio
#### HTML and Parsing: BeautifulSoup, html
#### Miscellaneous: tqdm, colorama, tabulate

## Architecture:
### Frontend: User interface built using gradio for real-time interaction and visualization.
### Backend: NLP processing and data management handled using langchain, openai, and chromadb.
### Database: Product data integrated and managed using FAISS/Chroma.

## Target Audience
Customers shopping for fashion products on Myntra or similar e-commerce platforms.

## Challenges Faced and Learnings
### Data Handling:
#### Challenges:
##### Data Cleaning: Ensuring that data from different sources was clean and in a consistent format for analysis and use within the app.
##### Integration: Merging various data types (text, images, and structured data) into a single cohesive dataset.
#### Learnings:
##### Effective Data Preprocessing: Learned advanced data cleaning techniques using pandas to handle missing values, data inconsistencies, and format discrepancies.
##### Modular Data Pipelines: Implementing a modular approach to data handling helped in maintaining clean and manageable code.
### Ranking:
#### Challenges:
##### Relevance and Accuracy: Ensuring that the product search results were relevant and accurately ranked based on user queries.
##### Performance: Balancing between complex ranking algorithms and performance to maintain a responsive UI.
#### Learnings:
##### Algorithm Optimization: Gained insights into optimizing ranking algorithms for both accuracy and performance.
##### User Feedback Loop: Leveraged user feedback to continually refine and improve the ranking logic.
### Embedded Storage:
#### Challenges:
##### Efficient Storage: Deciding on the best storage solutions for quick access to product information and search results.
#### Learnings:
##### Choosing the Right Tools: Explored different embedded storage
##### Data Retrieval Optimization: Implemented efficient data retrieval methods to minimize latency.
### UI Design:
#### Challenges:
##### User Experience: Designing an intuitive and user-friendly interface.
##### Responsiveness: Ensuring the app worked well across executions.
#### Learnings:
##### Gradio Proficiency: Gained extensive experience with Gradio to create dynamic and interactive UI components.

By addressing these challenges, significant improvements were made in data handling, ranking accuracy, storage efficiency, and user interface design. These learnings contributed to building a robust and user-friendly web application.

## Conclusion
The application showcases the power of combining semantic search and natural language processing. Key innovations include data preprocessing, embedding-based retrieval, and intuitive UI.

## Library Versions
As defiend in 'requirements.txt' file

Steps To Runt he Notebook

1. Import the notebook into Google Colab
2. Set the OpenAI API key appropriately
3. Download and place the necessaary files at appropriate location and modify the location int he notebook accordingly
4. Either select "Run All' or Run individual cells
5. The notebook will first start and except user's input for gradio interface for LangChain.
6. Once the gradio for LangChain is stopped manually, other cells below it can be executed to check out the results for LLamaIndex which too has a Gradio interface