# Celebrity_Face_Recognition
This is a machine learning project focused on classifying sports personalities into one of five well-known athletes using structured data or image inputs. The project demonstrates how ML models can be applied for classification tasks in a simplified sports-related context.
**Objective**
To build and deploy a machine learning model that can classify a given input as one of the following sports personalities:
1. Maria Sharapova
2. Serena Williams
3. Virat Kohli
4. Roger Federer
5. Lionel Messi 

**Technologies & Tools Used**
- Python
- Pandas, NumPy
- scikit-learn, openCV
- Matplotlib, Seaborn (for visualization)
- Jupyter Notebook
- Streamlit (for web interface)

**ML Workflow**
### 1. Data Collection
- Gather data relevant to each sports personality by using different interfaces(fatkun extension, google image scrapping etc.)

### 2. Data Preprocessing
- Clean missing or noisy data
- Resize/normalize images (for image classification)
- Detection of face and eyes using OpenCV

### 3. Model Selection
- Choose a classification algorithm (e.g., Logistic Regression, SVM, Random Forest)

### 4. Model Training
- Train on labeled data with proper splits (train/test/validation)
- Use cross-validation (Grid Search CV)

### 5. Model Evaluation
- Evaluate using metrics such as:
  - Accuracy
  - Precision & Recall
  - Confusion Matrix

### 6. Deployment
- Use **Streamlit** to build a simple, interactive web interface
- Users can upload an image or input features and get a classification result











