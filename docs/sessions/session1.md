# Session 1 – Foundation: Fabric & Copilot (60 min)

### Demo of Copilot in Fabric
Follow along in your own environment or just watch.

1. Locate the Copilot icon on the left navigation rail and the one inside Lakehouse/Notebook experiences. Confirm they both exist. 
![Copilot in Lakehouse](../assets/img/copilot_in_lakehouse.png)

2. In Power BI Service, open any existing report and open the Copilot pane (“Ask data questions”) to see Copilot inside reports. 
![Copilot for Report Creation](../assets/img/copilot_report_creation.png)


### Data Sourcing 
Create a Lakehouse, import data, and tranform with a Dataflow Gen2
 
1. Navigate to the workspace list and select the My Workspace.
![Workspace Navigation](../assets/img/workspace_navigation.png)

2. Create a Lakehouse:  New ► Lakehouse, name it **lh_demo**, then click **Create**. !
![Create New Item](../assets/img/create_item.png)

3. Search for **Lakehouse** and select the Lakehouse option
![Search Lakehouse](../assets/img/search_lakehouse.png)
![Select Lakehouse](../assets/img/select_lakehouse.png)

4. Name it **lh_demo**, then click **Create**. !
![Lakehouse Creation](../assets/img/create_lakehouse.png)

5. Upload the provided CSV or Parquet files into **/Files**.Right-click on the **/Files** folder in the Lakehouse and **Upload Folder**.
6. Select **Overwrite existing files** and then **Upload**.
![Overwrite Existing](../assets/img/overwrite_existing.png)

7. Create a Dataflow Gen2 that will transform the data into tables for our semantic model. Click **New Item** and search for **Dataflow**.
![Create New Item](../assets/img/create_item.png)
![Search Dataflow](../assets/img/search_dataflow.png)
![Select Dataflow](../assets/img/select_dataflow.png)

8.  Generate a Semantic Model:  Lakehouse ► **New semantic model** ► select your tables ► **Create**.
![New Semantic Model](../assets/img/new_semantic_model.png)
![Select Tables](../assets/img/select_tables.png)

9.  Open **Model view**. Create 1‑many relationships to match the screenshot below:
![Semantic Model](../assets/img/semantic_model.png)

10.   Use Copilot to create a report with the prompt: "Create me a report to show sales over time including both high-level and detailed information."
![Copilot Report](../assets/img/copilot_report_creation.png)  