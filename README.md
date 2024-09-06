# Invest Smart: A Consumer-Centric Investment Visualization Tool

## School: Computer Science, University of Nottingham, UK
## Academic Year: 2023-24

### Student Information
- **Name**: Aishwarya Shahu
- **Student ID**: 20607987

## Project Title
**Invest Smart: A Consumer-Centric Investment Visualization Tool**

### Module Code
COMPXXXX

## Project Overview
"Invest Smart" is a consumer-centric investment visualization tool designed to empower retail investors by providing an intuitive platform for monitoring and analyzing investment portfolios. The tool integrates both real-time and historical financial data to deliver detailed insights into investment performance, supporting data-driven decision-making. Utilizing Python and its robust visualization libraries, the tool offers interactive dashboards that simplify complex financial information, making it accessible even to non-expert users. Evaluation through various case studies demonstrates that "Invest Smart" effectively meets its design objectives, providing investors with actionable insights that align with their unique financial goals.

### Key Features
1. **Real-Time and Historical Data Integration**: The tool aggregates data from various sources, including APIs such as Yahoo Finance, to provide up-to-date information on stock prices, market trends, and other key financial indicators.
   
2. **Interactive Visualizations**: Utilizing Python libraries like Plotly and Dash, the tool offers interactive charts and graphs that enable users to explore their investment data in detail, including visualizations of realized and unrealized gains, dividends, and overall portfolio performance.

3. **Personalized User Experience**: The tool features customizable dashboards that cater to the unique preferences and needs of each investor. Users can track specific stocks, sectors, and industries, allowing them to focus on areas most relevant to their investment strategies.

4. **Evaluation of Investment Decisions**: The tool provides a framework for assessing buy and sell decisions based on historical performance data and moving averages, helping investors refine their trading strategies for better outcomes.

### Data Description
#### Datasets
- **Investment Data 2020-2024**: Detailed records of trading activities from Trading 212, including market buys, sells, dividend receipts, and other financial transactions. Data is organized into multiple sheets within an Excel workbook.
  
- **Company-Centered Metadata**: Detailed metrics for 83 stocks, including realized and unrealized gains, dividend distributions, and other key financial metrics.

#### Key Attributes
- `Transaction Date`, `Ticker`, `No. of shares`, `Price / share`, `Currency`, `Result (GBP)`, `Total (GBP)`, `Dividend`, `Stock Split Adjustments`, and more.

### Methodology
1. **Data Acquisition and Preprocessing**:
   - Data is acquired from Excel files and the Yahoo Finance API.
   - Preprocessing includes cleaning, normalization, and integration of data from multiple sources to ensure accuracy and consistency.

2. **Visualization Design**:
   - The tool uses a visualization pipeline that transforms raw investment data into actionable insights through structured stages of data processing and visualization mapping.
   - Visualizations include line charts, bar charts, and scatter plots that update in real-time based on user inputs and market changes.

3. **Implementation**:
   - Developed using Python with Dash and Plotly for the frontend, allowing for dynamic and interactive user interfaces.
   - Features include customizable dashboards, hierarchical color mapping, and interactive elements such as zooming, panning, and tooltips.

4. **Evaluation**:
   - The tool was evaluated through case studies that tested its effectiveness in delivering personalized financial insights. Results demonstrated the tool’s capability to enhance investment decision-making through dynamic visualizations and interactive features.

### Challenges
1. **Integration of Diverse Data Sources**: Ensuring robust data cleaning and normalization processes to integrate data from multiple platforms.
   
2. **Data Security and Privacy**: Implementing robust security measures, including encryption and secure authentication protocols, to safeguard user data.

3. **Balancing Technical Accuracy with Usability**: Designing visualizations that simplify complex financial metrics while retaining their accuracy and usefulness for retail investors.

### Future Work
- **Enhancing Data Integration**: Incorporating additional data sources and refining data integration processes to provide more comprehensive insights.
  
- **Expanding User Customization**: Adding more customization options for users to tailor their experience, including advanced filtering and personalized alerts.

- **Advanced Analytics**: Introducing machine learning models to provide predictive insights and advanced analytics for investment strategies.

### References
1. Liu et al., "Visualization Resources: A Survey", 2022.
2. Munzner, T. (2014). "Visualization Analysis and Design".
3. Ware, C. (2019). "Information Visualization: Perception for Design".
4. Yahoo Finance API Documentation.
5. Plotly and Dash Documentation.

## Acknowledgments
I would like to extend my deepest gratitude to Professor Robert S. Laramee for his invaluable guidance, support, and expertise throughout the development of this project. I also thank the entire visualization project group and the FinVis group for their collaborative spirit and constructive discussions. Lastly, I am deeply appreciative of my family and friends for their unwavering encouragement and support.

---

Feel free to contribute to this project by creating issues or submitting pull requests.
