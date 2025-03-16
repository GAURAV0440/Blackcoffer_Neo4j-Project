# Neo4j Graph Database with Cypher Queries using Python

This project showcases how to build and query a graph database using **Neo4j** with **Cypher language**, all through **Python**. It models relationships between people, movies, actors, directors, and genres — and exports query results to Excel for easy analysis.

## Tech Stack
- Python (Jupyter Notebook)
- Neo4j (Desktop Edition)
- Cypher Query Language
- Pandas (for data handling)
- Matplotlib (optional visualizations)

## How to Run

1. **Install Neo4j Desktop** and create a local DBMS
2. Run the notebook `Project.ipynb` in Jupyter/VS Code
3. Make sure your DB is running at:  
   `bolt://localhost:7687`  
   with user = `neo4j` and password = `xxxx` *(change if needed)*
4. All outputs including `.xlsx` will be generated automatically

## Output Files

- `Project.ipynb` – Main code notebook
- `final_graph_project.xlsx` – All above combined in one Excel file

## Conclusion

This project demonstrates a real-world graph data use-case — mixing logic, visualization, and data export. A great starting point for:
- Graph theory projects
- Movie/people recommendation engines
- Social network analysis
- Knowledge graphs
