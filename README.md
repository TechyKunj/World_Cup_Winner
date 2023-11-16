# Cricket World Cup Winner Prediction Project 🏏🌍🏆

## Introduction 🚀
Welcome to the Cricket World Cup Winner Prediction Project! 🏏 This Python project is your ultimate companion for predicting World Cup match outcomes. 🤖 It blends historical match data, team rankings, and player performances to unveil insights into potential winners.

## Installation 💻
Get ready to dive into the world of cricket predictions with these simple steps:

1. Install the `extract-wc-data` library:
    ```bash
    pip install extract-wc-data
    ```

2. Extract the latest World Cup data:
    ```python
    from ExtractWCData.get_latest_data import GetData
    data = GetData()
    df = data.get_data()
    df.to_csv('latest_data.csv')
    ```

3. Install the required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

4. Run the main project code provided.

## Usage 🚀
This project takes you through a fascinating journey:

- **Data Extraction**: Gather the latest World Cup data.
- **Model Training**: Utilize machine learning (Random Forest, Logistic Regression, Decision Tree).
- **Prediction**: Forecast match outcomes for upcoming fixtures.
- **Top Teams**: Discover top-performing teams based on the latest data.

## Contribution Guidelines 🤝
Ready to contribute? Awesome! Your ideas and improvements are more than welcome. Create a pull request and let's make this project even better. Please follow the coding standards and ensure thorough documentation.

## Licensing 📜
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for personal or commercial purposes.

## Running the Project 🏃
1. Execute the provided code to train the machine learning model.
2. Use the `predict_single_match` function to predict specific match outcomes. Example:
    ```python
    # Predicting the First Semi Final
    predict_single_match(rf, rankings, "India", "New Zealand")
    ```

## Prerequisites 🛠️
Ensure you have Python installed along with the required libraries mentioned in the installation section.

🏆 Let's dive into the excitement of the Cricket World Cup together! Enjoy predicting and may the best team win! 🌐🏏

## 🙏 Acknowledgments
Special thanks to PwSkills for providing the Cricket World Cup data.
Inspiration for this project came from the love of cricket and the desire to explore machine learning in sports predictions.
