Week 9 FIT3179 Homework: Public Transport Ridership in Malaysia
This project is a part of the Week 9 homework for the FIT3179 unit. It focuses on creating a proportional symbol map for public transport ridership in Malaysia using Vega-Lite and LaTeX for report generation.

Project Structure
plaintext
Copy code
week9fit3179HW/
│
├── data/                          # Contains all dataset files
│   ├── cleaned_ridership_data.csv
│   ├── merged_ridership_data.csv
│   ├── transport_stations_coordinates.csv
│   ├── summary_ridership_stats.csv
│   ├── tidy_ridership_data.csv
│   ├── ridership_headline.csv
│
├── visualizations/                 # Contains visual output(s)
│   ├── week9hwvisualization.png    # Final Vega-Lite visualization as PNG
│
├── code/                           # Contains Vega-Lite JSON spec and LaTeX report source
│   ├── week9hw_vegalite.json       # Vega-Lite JSON spec for the visualization
│   ├── week9hw_report.tex          # LaTeX file for report generation
│
├── reports/                        # Contains the compiled PDF report
│   ├── week9hw_report.pdf          # Final report in PDF format
│
└── README.md                       # This file
Data Description
The data/ folder contains several CSV files with public transport ridership data in Malaysia:

cleaned_ridership_data.csv: The cleaned dataset for use in the visualization.
merged_ridership_data.csv: Data merged from different sources.
transport_stations_coordinates.csv: Coordinates of transport stations.
summary_ridership_stats.csv: Summary statistics for the ridership data.
tidy_ridership_data.csv: Tidy version of the dataset.
ridership_headline.csv: Headline data points for key ridership statistics.
Visualization
The main visualization created for this homework is a proportional symbol map representing public transport ridership across different locations in Malaysia. The Vega-Lite JSON specification for this visualization is located in the code/ folder:

week9hw_vegalite.json: The Vega-Lite specification for the proportional symbol map.
The resulting visualization is saved as week9hwvisualization.png in the visualizations/ folder.

Report
The LaTeX report includes the methodology, the final visualization, and an analysis of the results. The LaTeX source file for the report can be found in the code/ folder, and the compiled PDF is in the reports/ folder.

week9hw_report.tex: LaTeX source file for the report.
week9hw_report.pdf: Compiled PDF report.
How to Use
View the Visualization:
You can view the final visualization in the visualizations/ folder as a PNG file.

Run the Vega-Lite Spec:
To reproduce the visualization, use the Vega-Lite specification from the code/ folder. You can run this using Vega Editor or any other Vega-Lite-supported tool.

Compile the LaTeX Report:
If you wish to modify or recompile the report, open the LaTeX file (week9hw_report.tex) in Overleaf or any LaTeX editor. After compiling, you will get the PDF report, which is already provided in the reports/ folder.

Conclusion
This project demonstrates the use of data visualization techniques to represent public transport ridership in Malaysia using proportional symbol maps. The report provides detailed analysis and insights based on the data.

License
This project is for educational purposes under the FIT3179 course and follows the appropriate academic policies.

