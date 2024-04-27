### EX10  Sentimental Analysis on Any Dataset Using Rapidminer

### AIM: 
To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
<div align = "justify">

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.


### Output:
```
Name: Lakshmi Priya P
Reg No: 212221230053
```
![326159967-a39295e5-e35e-484b-9b32-d1a25de91fdf](https://github.com/Lakshmipriya-P-AI/WDM_EXP10/assets/93427923/79f6d7cf-d98c-4307-8448-0acc03246be8)

![326159929-960c6418-1bbf-4727-ac6e-234698fefe2f](https://github.com/Lakshmipriya-P-AI/WDM_EXP10/assets/93427923/69aabf3f-a2f9-49a9-98b7-486e1e00c594)

![326159987-7c379dc1-db11-4d55-9a8c-8610351bb1eb](https://github.com/Lakshmipriya-P-AI/WDM_EXP10/assets/93427923/c531090b-17fc-4693-88af-69f33bf9c307)


### Result:
Thus sentimental analysis for twitter data using Rapidminer is done successfully.
