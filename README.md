# **Extraction and Visualization of Peru's Climate Data using Web Scraping**  

## **Description**  
This software extracts and analyzes specific climate information for any department or region in Peru using web scraping. It utilizes the **BeautifulSoup** library, along with other tools, to collect meteorological data from the **National Meteorology and Hydrology Service of Peru (SENAMHI)**.  

### **Main Features**  
- **Real-Time Data Extraction**: Users can input a location of interest and obtain the corresponding climate data.  
- **Data Storage**: The software saves collected data over time for future visualizations and analysis.  
- **Automated Data Update**: It ensures that stored data remains up-to-date while avoiding duplicates.  
- **Graphical Representation**: Includes visualizations for better interpretation of climate trends.  

### **Main Functions**  
- **`get_information(website)`**: Makes an HTTP request to the specified website and retrieves the response.  
- **`main()`**: Performs web scraping to obtain climate data and stores it in a CSV file. It also prompts the user to enter a location for analysis.  
- **`update_data(d, file)`**: Updates the CSV file, ensuring that the data remains accurate, up-to-date, and free of duplicates.  
- **`line_plot_graph(df, location)`**: Generates a line plot to visualize temperature trends over time.  
- **`scatter_plot_graph(df, location)`**: Creates a scatter plot representing temperature variations over time for a given location.  
