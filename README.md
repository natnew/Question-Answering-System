# Question-Answering-System 📖
### About
<img align="right" height="200" src="https://github.com/natnew/Question-Answering-System/blob/main/images/Birds%20Talking.png">

The Question Answering System is an AI-powered application designed to provide accurate and timely responses to user queries. Built on advanced natural language processing and machine learning techniques, it enables users to obtain relevant information from a large corpus of documents or knowledge bases. Whether you are a researcher, developer, or knowledge seeker, this system offers a powerful tool for efficient information retrieval and decision-making.

## Before getting started:

    🍴 To incorporate this repository into your own project, you can fork it.
    ⭐ In order to receive notifications about future improvements, please consider starring this repository.
For a short write up check out this [medium](https://medium.com/@natashanewbold) post. 

### Features
Upload documents (PDF, DOCX, TXT) and answer questions about them.

### Live Demo
Available on [Streamlit]()

### How It Works
1. A preprocessing step is performed to clean and prepare the text data.
2. The documents are split into smaller sections or splits of a specified size. 
3. The splits obtained from the previous step are stored, often using a vector store or a similar storage mechanism. 
4. The question and answering application retrieves splits from the storage based on certain criteria. 
5. An LLM, which refers to a language model, is utilized to generate an answer using a prompt that includes both the question and the retrieved splits.


### Running the Program
1. Clone the Repository: Start by cloning the [GitHub repository](https://github.com/natnew/Question-Answering-System/tree/main) containing the question and answering system.
2. Navigate to the cloned repository directory and install any [necessary dependencies or packages](https://github.com/natnew/Question-Answering-System/blob/main/requirements.txt).
3. Check if the question and answering system requires any specific configuration. Look for configuration files, such as config.yaml or settings.py, and modify them if necessary.
4. [Run the command]() to start the question and answering system.
5. Once the system is up and running, you can interact with it by [sending questions and receiving answers](https://github.com/natnew/Question-Answering-System/blob/main/data/Architectural%20Design%20Principles%20questions.md).


### Related Material

For more information and resources on building and improving question answering systems, refer to the following:<br>
[Research Papers on Question Answering Systems](https://arxiv.org/search/cs?query=question+answering)<br>
[Natural Language Processing (NLP) Tutorials and Courses](https://www.coursera.org/courses?query=nlp)<br>
[Coursera Courses](https://www.coursera.org/courses?query=nlp)<br>
[How I Built A Question-Answering System for Architects](https://medium.com/@natashanewbold)<br>



## License

See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).
