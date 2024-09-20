# EX-10 Sentimental Analysis on Any Dataset Using Rapidminer
### AIM: 
To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer.
### Description: 
### Procedure:
1) ***Import Excel data***<br>
    a. Drag the "Read Excel" operator from the IO folder onto the process canvas.<br>
    b. Double-click on the operator to open its configuration panel.<br>
    c. Specify the path to the Excel file you want to analyze.<br>
    d. Configure options such as sheet selection, header inclusion, etc.<br>
    e. Click on the "Run" button to execute the operator and import the Excel data.<br>
2) ***Perform sentiment analysis with Generate Attributes operator***<br>
    a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.<br>
    b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.<br>
    c. Double-click on the "Generate Attributes" operator to configure it.<br>
    d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").<br>
    e. Choose the sentiment analysis algorithm, "VADER."<br>
    f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.<br>
3) ***Interpret and export the results***<br>
    a. Analyze the sentiment analysis results from the generated visualizations.<br>
    b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.<br>
    c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.<br>
    d. Configure the file path and other settings for the Excel export.<br>
    e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.<br>
### Output:
<img src="https://github.com/user-attachments/assets/ee696682-4add-42c6-b6e9-78d6bf2f6139">
<img src="https://github.com/user-attachments/assets/008503b8-fd4e-45bc-85a9-632a544e2aa6">

### Result:
Thus,successfully executed to create a project for Sentimental Analysis on Any Dataset a Using Rapidminer.
