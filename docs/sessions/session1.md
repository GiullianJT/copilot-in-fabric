# Session 1 – Foundation: Fabric & Copilot (60 min)

### 1. Open your assigned Microsoft Fabric workspace in a browser. 
![Copilot and Fabric Logos](assets/img/copilot_logo.png)

2. Locate the Copilot icon on the left navigation rail and the one inside Lakehouse/Notebook experiences. Confirm they both exist. [Screenshot]
3. In Power BI Service, open any existing report and open the Copilot pane (“Ask data questions”) to see Copilot inside reports. [Screenshot]
4. ![Copilot and Fabric Logos](assets/img/copilot_logo.png)
5. Create a Lakehouse:  New ► Lakehouse, name it **Sales Lab**, then click **Create**. [Screenshot]
6. Upload the provided CSV or Parquet files into **/Tables**. Fabric should auto‑create Delta tables. [Screenshot]
7. If a table does not auto‑create, use **Create table** wizard and point it to the file. Keep column names as‑is.
8. (Optional) Create a simple Dataflow Gen2 that lands one of the files in the Lakehouse so you see both ingestion paths.
9.  Generate a Semantic Model:  Lakehouse ► **New semantic model** ► select your tables ► **Create**.
10. Open **Model view**. Create a 1‑many relationship **Sales[ProductID] → Products[ProductID]**.
11. Hide key columns and rename any cryptic columns to friendly business names (e.g., “Prod_ID” → “Product ID”).
12. Checkpoint: verify all tables are related, names are readable, and no errors appear in the model.
