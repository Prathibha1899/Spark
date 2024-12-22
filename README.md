# Spark  
This project demonstrates the use of **Apache Spark** to implement several important algorithms for distributed data processing. It covers the development and analysis of three core algorithms: **Word Count**, **Dijkstra’s Shortest Path**, and **Page Rank**. Through this project, I explored how Spark can be used to efficiently process large datasets in a distributed computing environment, and I gained insights into graph-based algorithms and the workings of Spark’s internal execution model.

### Key Highlights:
- **Word Count Algorithm**: A classic example of text processing, where Spark reads and processes text files to count word frequencies, while ignoring case, punctuation, and stop words. The output is sorted by word frequency.
- **Dijkstra's Shortest Path Algorithm**: Implemented to find the shortest path between nodes in a graph, where the graph's nodes and edges are represented in text files. Spark was used to process and compute the shortest paths from a source node to all other nodes.
- **Page Rank Algorithm**: Simulated a network of web pages and computed their ranks based on the links between them, using the Page Rank algorithm to evaluate the importance of each page in the network.

## Setup  
This project was developed using **Apache Spark** in **PySpark**. To set up the development environment, follow these steps:

1. **Install Apache Spark** by following the [PySpark installation guide](https://spark.apache.org/docs/latest/api/python/getting_started/install.html).
2. **Download Text Files**: For the Word Count and Page Rank algorithms, I used text data from **Project Gutenberg**. You can download any books in plain text format to use as input.
3. **Run the Scripts**: The Python scripts provided in the repository will process the text files, compute the results, and generate output files for each algorithm. The scripts also include parts of code that analyze the Spark job execution and visualize the stages via Spark’s WebUI.


