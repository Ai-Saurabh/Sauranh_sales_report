# Saurabh Store Data Analysis

This project involves analyzing the data from the "Saurabh Store" dataset to extract meaningful insights, including delivery times, packages stuck in transit, shipping delays, and other relevant metrics.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Workflow](#analysis-workflow)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

This analysis focuses on understanding the shipping performance, customer experience, and operational efficiency of the Saurabh Store. The primary objectives are to:

1. Calculate delivery times.
2. Identify packages stuck in transit.
3. Detect shipping delays.
4. Check SLA compliance.
5. Identify the most shipped items.

## Data Description

The dataset used in this project contains the following columns:

- **Order #**: Unique identifier for each order.
- **Ship By Date**: The latest date by which the order should be shipped.
- **Ship After Date**: The earliest date by which the order can be shipped.
- **Carrier**: The shipping carrier used for the order (e.g., USPS, UPS).
- **Service**: The shipping service level (e.g., Priority Mail, 2nd Day Air).
- **Receipt Date**: Date when the order was received.
- **Ship Date**: Date when the order was shipped.
- **Delivery Date**: Date when the order was delivered.
- **Days to Delivery**: Calculated number of days between the ship date and delivery date.

Additional columns are included to capture various aspects of the order and shipping process.

## Installation

To run the analysis, you'll need to have Python and the necessary libraries installed. Follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/saurabh-store-data-analysis.git

# Navigate to the project directory
cd saurabh-store-data-analysis

# Install dependencies
pip install -r requirements.txt
