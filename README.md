# AI-Driven Email Automation for E-Commerce

This project is an AI-driven application designed to automate the processing of email order requests and customer inquiries for a fashion store. The system categorizes emails, processes orders, and handles product inquiries, providing accurate and personalized responses based on the store's product catalog and stock status.

## Features:

- **Email Classification:**
  - Classifies incoming emails as either **"product inquiry"** or **"order request"** using advanced natural language processing (NLP) techniques.
  - Ensures accurate routing of emails to the appropriate processing pipeline.

- **Order Request Processing:**
  - Verifies product availability in stock for order requests.
  - Creates order entries with statuses such as **"created"** or **"out of stock"**.
  - Updates inventory levels after processing orders.
  - Generates production-ready response emails based on the order status, offering options like waiting for restock or selecting alternative products.

- **Product Inquiry Handling:**
  - Extracts relevant product information from inquiry emails.
  - Matches product inquiries with the store's product catalog.
  - Generates user-friendly responses containing product details such as descriptions, stock availability, and prices.
  - Scales to handle large product catalogs containing over 100,000 items.

## Tools and Technologies:

- **OpenAI GPT-4:** For natural language processing and generating responses.
- **Python:** Core programming language used for development.
- **Pandas:** For data manipulation and handling the Google Spreadsheet data.
- **Rapidfuzz:** For fuzzy matching product names to ensure accurate product identification.
- **Jupyter Notebook:** Environment for coding, testing, and documenting the project.

## Data Source:

The project uses a Google Spreadsheet Document, which can be accessed [here](https://docs.google.com/spreadsheets/d/1uWkz7nlLoMLOzgnTxvPe7sA3FISArbOaa5NacDlKZSU). The document contains the following sheets:

- **Products Sheet:** Includes fields like product ID, name, category, stock amount, detailed description, and season.
- **Emails Sheet:** Contains email data with fields like email ID, subject, and body.

## Usage Instructions:

To deploy this model and run it locally:

1. Clone the model (Run it in terminal or command prompt)

`git clone https://github.com/jahnavish/AI-Driven-Email-Automation-for-E-Commerce.git`

2. Clone the model directly in Jupyter:

Open a Jupyter Notebook on your local machine

Run shell commands by adding ! as the prefix before your command

`!git clone https://github.com/jahnavish/AI-Driven-Email-Automation-for-E-Commerce.git`

This will clone the repository directly in your Jupyter.

## Conclusion:

This project demonstrates the use of AI and LLMs to automate email processing for an e-commerce fashion store. It is designed to handle large volumes of emails and extensive product catalogs, providing a scalable and efficient solution for improving customer engagement and operational efficiency.
