# EpiRecipes Analysis and Suggester

## Description
EpiRecipes Analysis and Suggester is a comprehensive data analysis project and web application that explores a rich dataset of recipes from Epicurious. This project combines in-depth exploratory data analysis (EDA) with a user-friendly Streamlit application to suggest recipes based on available ingredients.

## Features
- **Exploratory Data Analysis (EDA)**: 
  - Analyze recipe ratings, preparation times, and nutritional content
  - Explore seasonal trends and popular ingredients
  - Investigate correlations between various recipe attributes

- **Recipe Suggestion Web App**:
  - Input available ingredients to receive personalized recipe suggestions
  - View detailed recipe information including ratings, nutritional facts, and instructions
  - Explore top common ingredients and app statistics

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Streamlit for web application development
- Jupyter Notebooks for exploratory data analysis

## Dataset
Dataset: https://drive.google.com/file/d/1Vpcz2_gbBN2NHRuk2E0OjOvzaNN1RD_K/view?usp=sharing
cleaned dataset : https://drive.google.com/file/d/1w_LOL1E4zv1Lcla4t787hpb93N-oiWWX/view?usp=sharing     

## video link
https://drive.google.com/file/d/1SiifNI8kpCPC037yPzJRwKVHxlLw7F9R/view?usp=sharing

The project uses the EpiRecipes dataset, which includes:
- Recipe titles and ratings
- Nutritional information (calories, protein, fat, sodium)
- Binary encoding of ingredients (1 for present, 0 for absent)
- Preparation time indicators (e.g., '22-minute meals')
- Seasonal and occasion tags

## Installation and Usage
1. Clone the repository:
   ```
   git clone https://github.com/Sunny110101/EpiRecipes-Visualization-Application.git
   ```
2. Install required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```
   streamlit run recipeStreamlit.py
   ```

## Project Structure
- `data/`: Contains the EpiRecipes dataset
- `notebooks/`: Jupyter notebooks with exploratory data analysis
- `src/`: Source code for data processing and analysis
- `app/`: Streamlit application files
- `requirements.txt`: List of required Python packages

## Contributing
Contributions to enhance the analysis or extend the application's features are welcome. Please feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Data source: [Epicurious](https://www.epicurious.com/)
- Inspired by the Kaggle dataset: [Epicurious - Recipes with Rating and Nutrition](https://www.kaggle.com/hugodarwood/epirecipes)
