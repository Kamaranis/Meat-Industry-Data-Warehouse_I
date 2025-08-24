# Meat Industry Data Warehouse

## 📄 Description

This project is a data warehouse solution for a fictional meat distribution company. The main objective is to analyze sales data from an ERP database to gain business intelligence insights. A data cube was developed to explore the information from different perspectives and to facilitate decision-making.

The project was developed as a solution to a company's request to better understand its sales performance, identify trends, and analyze key metrics such as sales by product, customer, location, and time.

## ✨ Key Features

*   **Data Extraction and Transformation:** The project includes the necessary scripts for the creation and loading of data into a Microsoft SQL Server database.
*   **Data Cube:** A data cube was designed and implemented to allow for multidimensional analysis of the sales data.
*   **Reporting and Visualization:** The results of the analysis are presented in reports and visualizations that are easy to understand.
*   **Technology Integration:** The project demonstrates the integration of Microsoft SQL Server with R for data analysis and reporting.

## 💻 Technologies Used

*   **Database:** Microsoft SQL Server
*   **Data Analysis and Visualization:** R, R Markdown
*   **Version Control:** Git and GitHub

## 📂 Project Structure

*   `BBDD_ERP_data.sql`: SQL script for creating and populating the database.
*   `meat business (I).Rmd`: R Markdown file with the analysis, code, and documentation of the project.
*   `meat-business--I-.html` / `meat-business--I-.pdf`: Reports generated from the R Markdown file.
*   `p_brand.html`: Additional HTML report.
*   `img/`: Directory containing images used in the reports.

## 🚀 Getting Started

### Prerequisites

*   Microsoft SQL Server
*   R and RStudio
*   Git

### Installation and Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Kamaranis/Meat-business-I.git
    ```
2.  **Set up the database:**
    *   Execute the `BBDD_ERP_data.sql` script in your Microsoft SQL Server instance to create the database and load the data.
3.  **Open the R project:**
    *   Open the `meat business (I).Rmd` file in RStudio.
    *   Install the necessary R packages (the list of packages should be at the beginning of the Rmd file).
4.  **Run the analysis:**
    *   Execute the code chunks in the R Markdown file to reproduce the analysis and generate the reports.

## 📊 Showcase

*(Aquí puedes añadir capturas de pantalla de tus informes o visualizaciones para mostrar el resultado de tu análisis. Por ejemplo, puedes incluir imágenes de los gráficos o tablas que se encuentran en los archivos HTML o PDF generados.)*

**Example:**

![Sales by Product Category](img/sales_by_product.png)
_This chart shows the sales distribution among the different product categories._

## 👤 Author

**[Tu Nombre]**

*   **LinkedIn:** [Tu Perfil de LinkedIn]
*   **GitHub:** @Kamaranis
