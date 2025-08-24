                                             Laptop Rule-Based Classifier


Project Description
This project implements a simple rule-based classifier to predict whether a laptop is recommended or not based on its specifications.
The rules are:
RAM ≥ 8 GB
Storage ≥ 512 GB
Price ≥Rs45000
If all conditions are met then Recommended = Yes, else No.
Dataset
The dataset contains 10 laptops with 4 features:
Processor (i3, i5, i7, Ryzen, etc.)
RAM (in GB)
Storage (in GB, SSD)
Price (in Rs)

Features:

Rule-based classifier using if-else logic

Runs predictions on predefined dataset

Takes real-time user input for prediction

How to Run:
click on jupyter.ipynb and directly open on Google colab
              

Example Output:

=== Laptop Dataset Predictions ===
Laptop 1 (i5, 8GB RAM, 512GB SSD, $700): Recommended = Yes
Laptop 2 (i3, 4GB RAM, 256GB SSD, $400): Recommended = No
...

=== Real-time Laptop Recommendation ===
Enter Processor (e.g., i5, Ryzen 5): i7
Enter RAM (GB): 16
Enter Storage (SSD in GB): 1024
Enter Price ($): 1200

Your Laptop (i7, 16GB RAM, 1024GB SSD, $1200): Recommended = Yes
