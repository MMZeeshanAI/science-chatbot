# Science Chatbot

This repository contains the Science Chatbot, an intelligent conversational agent designed to interact with users and provide scientific information, explanations, and guidance based on user queries. The chatbot leverages Natural Language Processing (NLP) to understand and respond to questions in a human-like manner, making it an engaging tool for learning and exploring various scientific topics.

## How to Run

Follow the instructions below to set up and run the Science Chatbot on your local machine or within a Docker container.

### Local Execution

1. **Clone the Repository:**

    Start by cloning the repository to your local machine:

    ```bash
    git clone https://github.com/MMZeeshanAI/science-chatbot.git
    cd science_chatbot
    ```

2. **Create and Activate Virtual Environment:**

    Ensure you have `virtualenv` installed. If not, install it using:

    ```bash
    pip install virtualenv
    ```

    Create and activate a virtual environment:

    ```bash
    python3.8 -m venv science_chatbot
    source science_chatbot/bin/activate  # On Windows, use `science_chatbot\Scripts\activate`
    ```

3. **Install Dependencies:**

    Install all the necessary dependencies using the provided `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application:**

    Start the chatbot by executing the `start.sh` script:

    ```bash
    ./start.sh
    ```

### Docker Container

Alternatively, you can run the Science Chatbot within a Docker container.

1. **Build the Docker Image:**

    Build the Docker image by running:

    ```bash
    docker build -t science_chatbot .
    ```

2. **Run the Docker Container:**

    Run the chatbot inside a Docker container:

    ```bash
    docker run -it science_chatbot
    ```

## Features

- **Natural Language Understanding:** The chatbot is capable of understanding and processing complex scientific queries.
- **Interactive Conversations:** Engage in dynamic conversations on a wide range of scientific topics.
- **Educational Tool:** Ideal for students, educators, or anyone with an interest in science, the chatbot provides detailed explanations and information.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing

Contributions are welcome! If you would like to contribute, please fork the repository, create a new branch, and submit a pull request with your changes.

## Contact

For any questions or inquiries, please contact Zeeshan Ansar at [mmzeeshanai@gmail.com].
