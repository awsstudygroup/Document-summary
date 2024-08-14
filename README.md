# DocuMentor

## Overview

AWS Document Summary is a simple demo that showcases the integration of Amazon Bedrock and the Anthropic Claude 3 Sonnet model with LangChain and Streamlit. This demo illustrates how to summarize documents efficiently using cutting-edge AI technologies. For further information, you can explore the following links:
- [Amazon Bedrock](https://aws.amazon.com/bedrock/)
- [Claude 3](https://www.anthropic.com/news/claude-3-family)

## Viewing Demo and Sample Data

- **Demo Video**: Access the `demo` folder to view the demonstration video.
- **Sample Data**: Explore the `samples` folder to find sample documents used in the demo.

## Setup Instructions

### Prerequisites
1. **Install Python**: Ensure that Python is installed on your system. Follow the [Python installation guide](https://docs.python-guide.org/starting/install3/linux/) for detailed instructions.
2. **Set Up Python Environment**: Create a virtual environment for this project. Refer to the [Python environment setup guide](https://docs.python-guide.org/starting/install3/linux/) for guidance.
3. **Set Up AWS CLI**: Install and configure the AWS CLI to interact with AWS services. Follow the [AWS CLI quickstart guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html).

### Steps to Set Up the Project

1. **Clone the Repository**: 
    ```bash
    git clone https://github.com/awsstudygroup/Document-summary.git
    ```

2. **Navigate to the Project Directory**: 
    ```bash
    cd Document-summary
    ```

3. **Install the Required Dependencies**: 
    ```bash
    pip3 install -r requirements.txt
    ```

4. **Run the Application**: 
    ```bash
    streamlit run Home.py --server.port 8080
    ```

    This command will launch the Streamlit app on port 8080. Open your web browser and navigate to `http://localhost:8080` to interact with theDocuMentor tool.

## Architecture

The architecture of theDocuMentor project integrates multiple components to achieve seamless document summarization. Below is an illustrative diagram of the system architecture:

![Architecture](./Architecture.png)

## Learning More About Prompt and Claude 3

- **Introduction to Prompt Design**: Learn the fundamentals of crafting effective prompts for AI models in this [Introduction to Prompt Design](https://docs.anthropic.com/claude/docs/introduction-to-prompt-design).
- **Claude 3 Model Card**: Gain deeper insights into the capabilities and limitations of the Claude 3 model by reviewing its [Model Card](https://www-cdn.anthropic.com/de8ba9b01c9ab7cbabf5c33b80b7bbc618857627/Model_Card_Claude_3.pdf).

## Contributing

Contributions are highly encouraged! If you wish to contribute to this project, please submit a pull request. Ensure that all code is thoroughly documented and tested before submission.

## License

This project is licensed under the MIT License. Please refer to the LICENSE file in the repository for more details.

## Contact

For any questions, issues, or feedback, feel free to reach out at [your email or contact information].

---

This guide provides a comprehensive overview and step-by-step instructions for setting up and contributing to theDocuMentor project.
