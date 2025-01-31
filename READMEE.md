Project Overview

The Personalized-Student-Recommendations project is a comprehensive quiz performance analysis tool that processes quiz data, extracts insights, and provides recommendations for improvement. It leverages Python libraries such as requests, numpy, matplotlib, rich, and sklearn to analyze quiz results, compare historical data, and visualize trends.

Key Features

Fetch Quiz Data: Retrieves quiz performance and historical data from APIs.
Analyze Performance: Computes accuracy, improvement trends, and mistake correction rates.
Compare Historical Data: Identifies trends in accuracy, score, and percentile ranking.
Generate Insights & Recommendations: Suggests improvement strategies based on performance metrics.
Visualize Trends: Uses Matplotlib to create performance trend graphs.
Display Reports: Uses rich to present structured and color-coded results in the terminal.
Installation and Usage

To install the project, follow these steps:

Clone the repository: git clone https://github.com/yash25112003/Personalized-Student-Recommendations.git
Navigate to the project directory: cd Personalized-Student-Recommendations
Install the required dependencies: pip install -r requirements.txt
Run the script: python main.py
The program will fetch the latest quiz data and historical records, analyze them, and display an enhanced performance report. Visual trend charts will be generated to help track improvement over time.

API Configuration

Update the API keys in the script to fetch quiz performance and historical data:

python
Insert Code
Run
Copy code
quiz_performance_api_key = "https://api.jsonserve.com/XgAgFJ"
historical_performance_api_key = "https://api.jsonserve.com/XgAgFJ"
Key Functions

get_quiz_performance_data(api_key: str) -> Dict: Fetches the latest quiz performance data.
get_historical_performance_data(api_key: str) -> List[Dict]: Retrieves past quiz performance data.
analyze_quiz_performance(current_quiz: Dict, historical_quizzes: List[Dict]) -> Dict: Computes accuracy, mistake correction rates, and performance improvements.
visualize_performance(current: Dict, historical: List[Dict]) -> None: Generates accuracy and score trend graphs.
display_enhanced_performance(result, historical_quiz_data): Displays a detailed quiz performance summary in a structured, color-coded table.
You

this is the readme.md file just mdify the scipt such that head topics are bold and line breaks are incldude properly

BLACKBOXAI

Here’s the modified README.md file with bold headings and proper line breaks for better readability:

Personalized-Student-Recommendations
This project is a comprehensive quiz performance analysis tool that processes quiz data, extracts insights, and provides recommendations for improvement. It leverages Python libraries such as requests, numpy, matplotlib, rich, and sklearn to analyze quiz results, compare historical data, and visualize trends.

Features
Fetch Quiz Data: Retrieves quiz performance and historical data from APIs.
Analyze Performance: Computes accuracy, improvement trends, and mistake correction rates.
Compare Historical Data: Identifies trends in accuracy, score, and percentile ranking.
Generate Insights & Recommendations: Suggests improvement strategies based on performance metrics.
Visualize Trends: Uses Matplotlib to create performance trend graphs.
Display Reports: Uses rich to present structured and color-coded results in the terminal.
Installation
Prerequisites
Ensure you have Python 3.7+ installed. Install dependencies using:

bash
Insert Code
Run
Copy code
pip install -r requirements.txt
Installation Steps
Clone this repository:

bash
Insert Code
Run
Copy code
git clone https://github.com/yash25112003/Personalized-Student-Recommendations.git
Navigate to the project directory:

bash
Insert Code
Run
Copy code
cd Personalized-Student-Recommendations
Install the required dependencies:

bash
Insert Code
Run
Copy code
pip install -r requirements.txt
Usage
Run the script:

bash
Insert Code
Run
Copy code
python main.py
The program will fetch the latest quiz data and historical records, analyze them, and display an enhanced performance report.
Visual trend charts will be generated to help track improvement over time.
API Configuration
Update the API keys in the script to fetch quiz performance and historical data:

python
Insert Code
Run
Copy code
quiz_performance_api_key = "https://api.jsonserve.com/XgAgFJ"
historical_performance_api_key = "https://api.jsonserve.com/XgAgFJ"
Key Functions
get_quiz_performance_data(api_key: str) -> Dict: Fetches the latest quiz performance data.
get_historical_performance_data(api_key: str) -> List[Dict]: Retrieves past quiz performance data.
analyze_quiz_performance(current_quiz: Dict, historical_quizzes: List[Dict]) -> Dict: Computes accuracy, mistake correction rates, and performance improvements.
visualize_performance(current: Dict, historical: List[Dict]) -> None: Generates accuracy and score trend graphs.
display_enhanced_performance(result, historical_quiz_data): Displays a detailed quiz performance summary in a structured, color-coded table.
Visualization
Trend Analysis Graphs: Line charts for accuracy and score trends.
Rich Console Reports: Color-coded tables and panels displaying quiz performance analysis.
Output

<img width="1318" alt="Image" src="https://github.com/user-attachments/assets/e532bb63-f78c-4835-8c1f-1c9982ff8b67" />
<img width="1318" alt="Image" src="https://github.com/user-attachments/assets/48ede3aa-2bd7-4178-8060-b24b5a4f8fe5" />

<img width="597" alt="Image" src="https://github.com/user-attachments/assets/6a93d625-0327-4959-84b2-0e3e385505ca" />
<img width="597" alt="Image" src="https://github.com/user-attachments/assets/d4feab6e-b970-4124-8f0a-2ca0a98ac3e0" />