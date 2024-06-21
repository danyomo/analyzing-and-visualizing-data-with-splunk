
# Analyzing and visualizing data with splunk

## Objective
analyse and visualize the data  prepared in a software tool called Splunk
## Dataset

Data was collected and structured by the Fraud team. This dataset consists of payments from various customers made in different periods and amounts. The feature columns include:

1. **Step**: This feature represents the month from the start of the simulation. The steps represent four months that the simulation ran virtually.
0: May</break>
1: June
2: July
3: August
2.  **Customer**: Customer ID
3.  **Age**: Categorised age
0.0: <= 18
1.0: 19 - 25
2.0: 26 - 35
3.0: 36 - 45
4.0: 46 - 55
5.0: 56 - 65
4.  **Gender**: Gender of the customer
F: Female
M: Male
5.  **PostcodeOrigin**: The postcode of origin/source.
6.  **Merchant**: The merchant's ID. 
7.  **Category**: Category of the purchase. 
8.  **Amount**: Amount of the purchase.
9.  **Fraud**: Target variable that shows if the transaction is fraudulent - 1 or non-fraudulent - 0.

## File Structure

The project directory structure is organized as follows:

- **README.md**: This readme file providing an overview of the project.
- **dataset/**: Directory containing the dataset files.
- **splunk dashboard/**: contains splunk dashboard.

## Getting Started

To get started with the analysis, follow these steps:
1. **Clone the Repository**: Clone the project repository to your local machine.

    ```bash
    git clone <url>
    ```
2.  Install Splunk Enterprise on your computer.
3.  Using the “prepared_data” file in dataset, import this file into Splunk. 
4.  Study the file using the “Interesting Fields” section in Splunk. This tells you about the data you’re using.

## view the dashboard
dwnload the file in splunk dasboard folder and view


