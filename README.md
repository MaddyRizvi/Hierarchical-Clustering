# Mall Customers Segmentation using Hierarchical Clustering

This project implements **Hierarchical Clustering** on the **Mall Customers dataset** to segment customers based on their **Annual Income** and **Spending Score**. **This project can be easily adapted to work with other datasets** containing different or additional independent variables.

## 📊 Dataset

The dataset used is `Mall_Customers.csv`, which contains information about:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

## 📁 Project Structure

```
├── Mall_Customers.csv
├── hierarchical_clustering.py            # Python script for hierarchical clustering
├── README.md
└── CONTRIBUTING.md
```

## ⚙️ Requirements

Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn scipy
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MaddyRizvi/Hierarchical-Clustering.git
   cd Hierarchical-Clustering
   ```

2. Make sure the `Mall_Customers.csv` file is present in the project directory.

3. Run the script:
   ```bash
   python clustering.py
   ```

## 📈 Output

- A **dendrogram** to determine the optimal number of clusters.
  
  ![Image](https://github.com/user-attachments/assets/67448c22-31fe-496a-9829-a11b85c07238)

- A **scatter plot** displaying customer segments based on hierarchical clustering.

  ![Image](https://github.com/user-attachments/assets/a942662d-182e-4686-8c4b-ee1fc19dd63a)

## 📌 Clustering Details

- **Algorithm**: Agglomerative Hierarchical Clustering
- **Distance Metric**: Euclidean
- **Linkage Method**: Ward's Method
- **Features Used**: Annual Income and Spending Score
- **Number of Clusters**: 5 (determined using the dendrogram)

## 🧠 Understanding the Clusters

Each cluster groups customers with similar income and spending habits. This segmentation can help in:

- Targeted marketing
- Customer profiling
- Business strategy development

## 👐 Contributing

Want to improve or add new clustering techniques? Read our [CONTRIBUTING.md](CONTRIBUTING.md) to get started.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
