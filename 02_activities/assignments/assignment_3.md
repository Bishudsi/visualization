# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
      ***I have used the Building asset Inventory dataset and Python to create an api connection to the dataset along with packages like matplotlib to generate the visualization.***

      ***I have downloaded the csv file and used excel to interpret and create visualization, I have primarily focussed on management, with an assumption that the management is directly associated with Building Type and Jurisdiction.***

    > Who is your intended audience? 
      ***This analysis has been conducted with city management as the intended audience.***
    
    > What information or message are you trying to convey with your visualization? 
      ***This analysis has been conducted with city management as the intended audience, with the primary objective of identifying regions that may require additional resource allocation.***
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
      ***This analysis has been conducted with city management as the intended audience, with the primary objective of identifying regions that may require additional resource allocation. It is important to note that the current visualization has certain limitations, as it does not account for population counts within each region. Consequently, the results should be interpreted with caution, and further refinement of the analysis—incorporating population data—is recommended to ensure a more accurate assessment of regional needs.***
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
      ***For the purpose of data visualization in Python, I have utilized an API that retrieves data directly from the original source. This approach ensures that the data remains stable and is less prone to unexpected changes. As a result, the code can be executed by any user, promoting reproducibility and consistency in the generated visualizations across different runs. To support transparency and ease of access, I have attached both the Excel file and the corresponding Jupyter Notebook (.ipynb) file to the project branch for reference.***

      ***For the visualization, I have used an Excel file containing the required dataset. As the analysis is based on a static file, the visualizations remain consistent each time the file is used, ensuring repeatability and uniformity in the results.***
    
    > How did you ensure that your data visualization is accessible?
      ***I have made an effort to utilize publicly available data sources, thereby eliminating the need for user authentication or access validation. Additionally, I have created an Excel copy of the dataset, which can be stored locally and accessed by any user, further supporting ease of use and broad accessibility.***  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
      ***Both city management and local communities will be able to analyze the distribution of various building types within their respective regions. This information can serve as a basis for informed discussions between city management, municipal authorities, and community members. Such dialogue can help identify areas that may require additional efforts or interventions to enhance the overall quality of living within each community***
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
      ***The idea was to analysis and identify the various types of building management and building classifications present in each region. Accordingly, the primary columns selected for analysis were City and Building Type. It was further assumed that each city should have an associated management body responsible for overseeing such buildings. Based on this assumption, the focus shifted to the Management attribute, under the premise that each management entity would be directly linked to a specific building type.  ***
    
    > What ‘underwater labour’ contributed to your final data visualization product?
      ***A significant amount of foundational work—often not visible in the final output—contributed to the development of the data visualization. This included identifying appropriate and publicly accessible data sources, cleaning and structuring the data for consistency, handling missing or ambiguous entries, and making assumptions where necessary (e.g., linking building types with management bodies). Additionally, attention was given to selecting the most relevant attributes for analysis, ensuring reproducibility by using static or API-based data sources, and designing visual outputs that would be intuitive and informative for both city management and community stakeholders.***

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
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
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
