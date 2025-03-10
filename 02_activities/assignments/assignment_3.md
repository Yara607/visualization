# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    I used Python (Plotly) and Excel to create my data visualizations. In Python, I used the Plotly library to create an interactive scatter plot, while in Excel, I used an area chart to represent the economic impact of tourism. These tools allowed me to effectively visualize trends and relationships within the dataset.

    > Who is your intended audience? 
    My intended audience includes policymakers, economists, tourism industry stakeholders, and researchers who analyze the economic impact of tourism. The visualizations provide insights into visitor spending and tourism receipts, helping decision-makers understand trends and make data-driven policy recommendations.
    
    > What information or message are you trying to convey with your visualization? 
    My visualizations aim to show the economic impact of tourism by comparing visitor spending and tourism receipts. The scatter plot in Python highlights the relationship between these two factors across different impact categories (e.g., Total, Direct). The area chart in Excel provides a clearer view of the overall trends in tourism revenue over different categories.These visualizations help illustrate how tourism contributes financially and how spending patterns may influence economic decisions.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive (Data Accuracy & Clarity):  I ensured that the data was accurately represented in both visualizations, with no distortions or misinterpretations. 
    In Python, the X-axis represents Visitor Spending, and the Y-axis represents Tourism Receipts, with different colors and symbols to represent different Impact categories (Total, Direct). This ensures that each category is represented distinctly and accurately. 
    In Excel, the X-axis represents ID numbers (from 1 to 15), which correspond to each row in the dataset. The Y-axis represents the amounts in USD for both Visitor Spending and Tourism Receipts, ensuring that the data is clearly presented and easy to follow without misrepresentation. 
    All the axes are correctly labeled to maintain data accuracy, and the legend in both visualizations helps identify the variables represented, which is crucial for avoiding confusion or misinterpretation of the data.Perceptual (Ease of Interpretation):
    I chose a scatter plot in Python because it effectively shows relationships between Visitor Spending and Tourism Receipts. I used different colors and marker shapes to differentiate Impact categories, making it easier to interpret trends.
    In Excel, an area chart was used to highlight overall trends, making comparisons more intuitive.
    Aesthetic (Visual Appeal & Readability): 
    In Python, I customized colors, font sizes, and marker styles to enhance readability.
    In Excel, I adjusted the chart title, axis labels, and area fill transparency to make the visual clear and professional. 
    I ensured contrast between colors so that different series are easily distinguishable.
    By following these principles, I made the visualizations both informative and visually engaging, ensuring that key insights are easily understood.

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    For Python (with reproducibility in mind):    To ensure that my data visualizations are reproducible, I used Python for one of the visualizations. Python code allows me to share the script, which contains all the steps taken to load the data, clean it, create the visualizations, and customize them. I ensured reproducibility by using np.random.seed(123) in Python to set a fixed random seed, which ensures that the data visualizations generated from the dataset will be consistent each time the code is executed. This allows the results to be easily reproduced on different systems or by others with the same dataset.
    For Excel (with the limitations of reproducibility):In Excel, the chart can be created manually by following specific steps. However, Excel does not inherently support the reproducibility of the visualization, as there is no automated way to regenerate the same chart if the data or steps are changed. The process is not scripted, and recreating the chart requires manual intervention, so it cannot be considered fully reproducible in the same way as Python. In fact the chart's data source and settings are preserved in the file, so anyone with access to the file can view and replicate the chart as needed. However, this method relies on manual steps, and the exact process might vary depending on how someone interprets the instructions.
    If the tool I used to create the visualizations (such as Excel) is not easily reproducible, this could present challenges for others who want to reproduce the work. Without clear instructions or code, the visualizations might not be easily recreated, and others may not fully understand how the results were achieved. This could limit the transparency of the work and make it harder to validate or build upon the analysis.

    
    > How did you ensure that your data visualization is accessible?  
    Clear Labels and Titles: In both Python and Excel visualizations, I made sure to clearly label the X and Y axes, as well as provide titles for each chart. This helps users understand what the axes represent and the purpose of the visualization. For example, in the Python plot, I included axis labels for "Visitor Spending" and "Tourism Receipts," and in Excel, I ensured that both axes were labeled appropriately.
    Color and Contrast: I used contrasting colors (orange and green) for the different impact categories in Python, ensuring they are distinguishable even for those with color vision deficiencies. While Excel uses color in the area chart, I made sure the contrast is high enough for easy differentiation between the data series.
    Legend and Symbols: In the Python scatter plot, I included a legend to specify the meanings of the colors and symbols, helping users interpret the data. I used different symbols (circle and square) for different impact categories (Total and Direct), which also provides accessibility for people who may have difficulty distinguishing colors.
    Font Choices and Size: For both Python and Excel, I used clear, easy-to-read fonts with appropriate sizing. In Python, the titles and axis labels used legible fonts (Arial and Verdana), and in Excel, I ensured that the font size was large enough for clarity.
    By incorporating these elements, I aimed to make the visualizations accessible to a wider audience, including those with visual impairments or other accessibility needs.

    > Who are the individuals and communities who might be impacted by your visualization? 
    Researchers and Academics: Researchers in economics, tourism, and social sciences can use the visualizations as a tool to explore relationships between visitor spending and tourism receipts. The data and visual insights can support academic studies, papers, or research reports related to economic impact analysis in the tourism sector.
    Local Communities and Residents: Residents of tourist areas can benefit from understanding how tourism impacts the local economy. For example, local businesses, workers, and residents may be able to see the positive (or negative) effects of tourism spending, which could influence their support for certain tourism-related initiatives or policies.
    Investors and Business Leaders: Investors and business leaders may use the visualizations to understand market trends and the financial implications of tourism on the economy. The insights could help them make informed decisions regarding investments in tourism-related sectors or businesses.
 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I focused on the most relevant features that directly answer the main question of the visualization: the relationship between tourism spending and receipts. Specifically, I chose the Visitor Spending and Tourism Receipts as the key variables, as they are central to understanding the economic impact of tourism.  The Impact category (e.g., Total, Direct) was included to provide deeper insights into the segmentation of the data, allowing for a more detailed understanding of how different levels of impact (Total vs. Direct) contribute to the overall tourism economy.
    Additionally, given the capabilities of the tools I used (Python and Excel), I made selections based on what could be easily represented and interpreted in the context of both tools. In Python, I had the flexibility to handle more complex data manipulations, while in Excel, I focused on a simpler representation of the key variables.
    I intentionally excluded variables that would have cluttered the visualization or detracted from the main message.

    > What ‘underwater labour’ contributed to your final data visualization product?
    I spent time analyzing the dataset to understand the relationships between the features and and making decisions about which features were most relevant to the final visualization. For example, I had to determine that Visitor Spending and Tourism Receipts were the core variables for my analysis and visualization, while excluding less relevant columns.
    he design of the visualizations involved several decisions to ensure they were clear, effective, and aesthetically pleasing. This included choosing the right chart types (scatter plot and area chart), selecting appropriate colors and symbols, and formatting axis labels for clarity. 
    I used the np.random.seed(123) method to ensure that the results were consistent and reproducible every time the script is run. For Excel, I had to manually save the file in a way that ensured the data and chart would remain intact when reopened.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09/03/2025`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
