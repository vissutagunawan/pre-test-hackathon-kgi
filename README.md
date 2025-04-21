# Hackathon : Empowering Energy through Artificial Intelligence

![Images](./Assets/hackathon-geoscience.png)

Welcome to the KGI - Empowering Energy through Artificial Intelligence Hackathon!
This event is your gateway to exploring how artificial intelligence can revolutionize the energy sector. Throughout this hackathon, you’ll design, build, and deploy machine learning models tailored to real-world challenges in Sub-surface, Mine Planning/Operation & Geo Technical, Facility Management & Production Optimization — all using Azure Machine Learning and powerful Python notebooks.

This guide is crafted to help you navigate the process with clarity and confidence. Follow each step to build impactful AI solutions that support smarter energy decisions.

🕒 Estimated Time to Complete: 2.5 to 4 hours

We’ve structured each activity to maximize your learning, creativity, and success. Get ready to innovate!

## 📂 Instructions
Inside the `Case_[case_number]` folder, you will find the instructions and datasets specific to each case in this hackathon.

| Folder                | Description                                               |
|-----------------------|-----------------------------------------------------------|
| [Case_1](<Case_1>)    | Reservoir Production Prediction using Machine Learning    |
| [Case_2](<Case_2>)    | Volve Log Prediction                                      |
| [Case_3](<Case_3>)    | Silica Quality Prediction in Mining Process               |

## 📌 Rules and Guidelines
### 🔀 Pull Requests

1. **Branching:** 
   - Create a new branch from the `main` branch for any changes or new features.
   - Use a descriptive branch name, such as `hackathon/[your_team_name]`.

2. **Commits:** 
   - Keep commits small and meaningful.
   - Each commit should focus on a single task or update.

3. **Pull Request:** 
   - Submit pull requests with a clear summary of what was changed or implemented.
   - Reference any issues or milestones when relevant.

### ⚙️ Working in Azure Machine Learning
1. **Setup:**
   - Confirm that you have access to an Azure Machine Learning workspace.
   - Clone this repository to your local machine or directly into the Azure workspace.

2. **Environment:**
   - Create a Python environment and install all necessary packages.
   - Maintain a `requirements.txt` file inside each `Case_[case_number]` folder.

3. **Notebooks:**
   - Open or create Jupyter notebooks within Azure Machine Learning Studio.
   - Keep notebooks organized and well-documented with markdown cells to explain your code and results.
   - Develop your models within these notebooks, ensuring clarity and coherence in your explanations.

4. **Execution:**
   - Run the notebooks in sequence to maintain the correct flow of data processing and model training.
   - Validate results, and carefully document any issues or anomalies that arise.

### 🤖 Model Creation
1. **Feature Engineering:** 
   - Perform essential data preprocessing steps, including normalization, feature selection, and handling missing values.

2. **Model Selection:** 
   - Experiment with various machine learning and deep learning models such as Linear Regression, Random Forest, and Neural Networks.

3. **Training:** 
   - Split your data into training and testing sets.
   - Train your models using suitable techniques and hyperparameters.

4. **Evaluation:** 
   - Evaluate model performance using suitable metrics like MAE, RMSE, and others
   - Document and compare the results across different models to identify the best performer.

### 🚀 Submitting to GitHub
1. **Updates:**
   - Regularly update your local branch with the latest changes from the main branch to avoid conflicts.

2. **Commits:**
   - Make meaningful commits with clear messages that describe the changes made.

3. **Push:**
   - Push your local branch to GitHub using the command:

   ```sh
   git push origin hackathon/[your_team_name]
   ```