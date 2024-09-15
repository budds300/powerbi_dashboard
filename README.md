# Business Intelligence Solution Project

## Introduction
This project aims to design and deliver an end-to-end business intelligence solution for a client using the CRISP-DM framework. The client has collected transactional data for the year 2019 but has not been able to leverage it effectively. Our goal is to analyze this data and generate a report that identifies key opportunities to increase sales and improve operational efficiency.

## Project Overview
### Business Objectives
The client requires insights on the following key questions:
1. Total Revenue: How much money did we make in 2019?
2. Seasonality: Can we identify any seasonality in the sales?
3. Product Performance: What are our best and worst-selling products?
4. Sales Trends: How do sales compare to previous months or weeks?
5. Geographic Distribution: Which cities are our products delivered to most?
6. Product Categories: How do product categories compare in terms of revenue generated and quantities ordered?
7. Additional Insights: Provide any additional insights that can be derived from the data.

Products with unit prices above $99.99 should be labeled as high-level products; otherwise, they should be categorized as basic-level products.

## Data Overview
The dataset is split into two parts:
1. **First Half (January to June 2019)**: Data collected in Excel and saved as CSV files. Available via OneDrive.
2. **Second Half (July to December 2019)**: Data stored in a remote database.

## Database Credentials
- **Server Name**: dap-projects-database.database.windows.net
- **User**: capstone
- **Password**: Z7x@8pM$2w
- **Database Name**: dapDB

## Methodology
The project follows the CRISP-DM framework to provide actionable insights based on the client's 2019 transactional data. This structured approach involves:
1. **Business Understanding**: Defining business objectives.
2. **Data Understanding**: Collecting, describing, and exploring the data to identify quality issues.
3. **Data Preparation**: Cleaning and preparing the data, including integration and transformation.
4. **Evaluation**: Assessing the results and validating the findings.
5. **Deployment**: Delivering the final report and recommendations using Power BI.

## Deliverables
- A comprehensive Power BI report addressing the client's key questions.
- Visualizations and dashboards that highlight key insights.
- Recommendations for leveraging the findings to drive more sales and improve efficiency.

## Tools and Technologies
- **Python/Pandas**: For data cleaning, preparation, and analysis.
- **SQL**: For querying the database and extracting relevant data.
- **Excel/CSV**: For handling the first half of the dataset.
- **Power BI**: For data visualization and dashboard creation.
- **Jupyter Notebook/VS Code**: For code development and documentation.

## Installation Instructions
To set up the environment and install necessary software and dependencies for this project, follow these instructions:

1. **Python Installation**:
   - Download and install Python from [python.org](https://www.python.org/).

2. **Create a Virtual Environment**:
   - Navigate to the project directory:
     ```bash
     cd path/to/your/project
     ```
   - Create a virtual environment:
     ```bash
     python -m venv env
     ```
   - Activate the virtual environment:
     - **Windows**:
       ```bash
       .\env\Scripts\activate
       ```
     - **Mac/Linux**:
       ```bash
       source env/bin/activate
       ```

3. **Install Python Packages**:
   - Use pip to install the required Python libraries:
     ```bash
     pip install -r requirements.txt
     ```

4. **Power BI Installation**:
   - Download and install Power BI Desktop from [Microsoft Power BI](https://powerbi.microsoft.com/desktop/).
   - Follow the setup instructions provided in the Power BI documentation to configure your environment.

5. **Database Access Setup**:
   - Ensure you have the necessary credentials and permissions to access the remote database. Use the provided credentials to connect to the database.

6. **Configure Your Development Environment**:
   - For code development and documentation, you can use Jupyter Notebook or VS Code. Install these tools if they are not already on your system.

## Usage
### Running the Analysis Scripts
1. Ensure all required libraries are installed as per the Installation Instructions.
2. Download and extract the dataset files from OneDrive and the remote database.
3. Run the provided Python scripts in the Jupyter Notebook (i.e., the `.ipynb` file) to perform data cleaning and analysis, and save the cleaned data for Power BI manipulation.

## Data Schema
**Orders Table**: Contains order details.
- **Order_ID**: Unique identifier for each order.
- **Product**: Name of the product.
- **Quantity_Ordered**: Number of units ordered.
- **Price_Each**: Price per unit.
- **Purchase_Address**: Address where the product was delivered.
- **Category**: Category of the product.
- **Level**: High-level or basic-level classification based on price.
- **Total_Sales**: Total sales amount for the order.
- **State**: State where the product was delivered.

## Code of Conduct
- Be respectful and constructive in your feedback.
- Follow the project's coding standards and guidelines.
- Ensure that all contributions are well-documented and tested.
- Collaborate openly and share knowledge with the team.

## Contributing
To contribute to this project:
1. **Fork** the repository on GitHub.
2. **Create** a new branch for your changes.
3. **Make** your changes and test them thoroughly.
4. **Submit** a pull request with a clear description of your changes.
5. **Review** and address any feedback provided during the pull request review.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Special thanks to the contributors and mentors who provided guidance and support throughout this project.
- Thanks to the developers and communities behind the tools and libraries used in this project.



## Authors
 
**1. Tamminga Budds**  
[![GitHub](https://img.shields.io/badge/GitHub-budds300-blue?logo=github)](https://github.com/budds300)


