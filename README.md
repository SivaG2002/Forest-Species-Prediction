
# 🌲 Forest Species Prediction

The **Forest Species Prediction** app is designed to classify forest types based on various environmental features, such as elevation, aspect, slope, and proximity to water bodies and roads. This tool can assist **ecologists**, **forestry experts**, and **environmental scientists** in understanding and predicting the distribution of different forest ecosystems.

---

## 🚀 Key Features
- **Accurate Predictions**: The app uses **Random Forest** and **Decision Tree** algorithms to achieve high accuracy. After testing, the **Random Forest** model was selected for its superior performance, achieving a **95% accuracy** in classifying forest types.
  
- **User-Friendly Interface**: Built with **Streamlit**, the app provides an intuitive and interactive user interface for ease of use, allowing users to input environmental data and receive instant forest type predictions.

---

## 🛠️ Technologies Used
- **Python**: Core programming language for building the application.
- **Streamlit**: Framework for developing the web interface.
- **Scikit-learn**: Machine learning library for building and fine-tuning predictive models.
- **Pandas**: Data manipulation and preprocessing.
  
### Machine Learning Algorithms
- **Random Forest**: Final model chosen due to its high accuracy in handling environmental data.
- **Decision Tree**: Initially tested for comparison but found less effective compared to Random Forest.

---

## 📊 Dataset
The model is trained using the **Covertype Dataset** from the **UC Irvine Machine Learning Repository**. This dataset consists of various environmental attributes associated with different forest cover types, including:
- Elevation
- Aspect (direction of the slope)
- Slope (degree of incline)
- Distances to water bodies and roads
- Soil type
- Wilderness area designation

> [Covertype Dataset - UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/covertype)

---

## 🖥️ User Interface

The app offers an interactive, user-friendly interface for easy navigation and visualization of the forest cover predictions. Below are some screenshots of the app:

### 🌍 Home Page
![Forest Feature Input](https://github.com/user-attachments/assets/36f62a2e-6792-4ac3-a02f-980174ef58be)

---

### 📊 Input Form for Forest Features
![Prediction Results](https://github.com/user-attachments/assets/08a10a72-b76d-4b15-9a7f-4a352a746b3c)

---

### 🌲Result
![{7A1B1D0F-F80D-4AB7-A640-914358770041}](https://github.com/user-attachments/assets/9f7d8b24-d3a1-4a4e-b1e3-7f47f21e5ab7)


---

## 🔧 How to Run the Project

To run this project on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SivaG2002/Forest-Species-Prediction.git
   ```

2. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

3. Input the environmental features in the web interface and predict the forest species!

---

## 📚 Future Improvements
- **Integration with GIS**: Incorporating geographical maps for better visualization of predicted forest regions.
- **Additional Features**: Implementing real-time data from environmental sensors.
- **Model Enhancement**: Fine-tuning the model further by experimenting with deep learning techniques.

---

## 📝 License

This project is open-source and available under the MIT License.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/Forest-Species-Prediction/issues).

---

### 🌟 Don't forget to leave a star if you found this helpful!

---

