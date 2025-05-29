# Session 1 – Foundation: Fabric & Copilot (60 min)

## Session Overview

In this session, you will get hands-on experience with Microsoft Fabric and Copilot. You’ll create a Lakehouse, import data, transform it with Dataflow Gen2, and generate a semantic model for analytics.

---

## Step-by-Step Instructions

### Demo of Copilot in Fabric

Follow along in your own environment or just watch.

1. **Locate the Copilot icon** inside the Lakehouse SQL analytics endpoint experience. It will be in the top ribbon as pictured below.

    ![Copilot in Lakehouse navigation](../assets/img/copilot_in_lakehouse.png)

2. **Open Copilot in the Power BI Service.**  
   Open any existing report and open the Copilot pane to see Copilot inside reports by clicking on the Copilot icon in the top ribbon as pictured below.

    ![Copilot for Report Creation in Power BI](../assets/img/copilot_report_creation.png)

---

### Data Sourcing

Create a Lakehouse, import data, and transform it with a Dataflow Gen2.

3. **Navigate to the workspace list** and select **My Workspace** (You may also use a standard workspace as long as it is on Fabric or Premium Capacity).

    ![Workspace Navigation](../assets/img/workspace_navigation.png)

4. **Create a Lakehouse:**  
   Click **New item** to open the artifact library.

    ![Create New Item](../assets/img/create_item.png)

5. **Search for "Lakehouse"** and select the Lakehouse option.

    ![Search Lakehouse](../assets/img/search_lakehouse.png)

6. **Name it `lh_demo`** and click **Create**.

    ![Lakehouse Creation](../assets/img/create_lakehouse.png)

7. **Upload the provided Data folder**  
   [Download here](../downloads/Content.zip) and upload into **/Files**. Right-click on the **/Files** folder in the Lakehouse and select **Upload Folder**.

    ![Upload Folder](../assets/img/upload_folder.png)

8. Click the folder icon and browse to select the data files you downloaded. **Select "Overwrite existing files"** and then click **Upload**.

    ![Overwrite Existing Files](../assets/img/overwrite_existing.png)
    ![Upload Folder Now](../assets/img/upload_folder_now.png)

9. **Create a Dataflow Gen2**  
   Click **New Item** and search for **Dataflow**.

    ![Create New Item for Dataflow](../assets/img/create_item.png)
    ![Search Dataflow](../assets/img/search_dataflow.png)
    ![Select Dataflow](../assets/img/select_dataflow.png)

10. **Import the `df_demo.pqt` file**  
    [Download the template](../downloads/df_demo.pqt) if needed.

    ![Import Dataflow Gen2](../assets/img/import_pqt.png)

11. **Configure the Lakehouse Connection**  
    Click the yellow button, sign in if needed, and click **Create**.

    ![Configure Connection](../assets/img/configure_connection.png)
    ![Lakehouse Connection](../assets/img/lakehouse_connection.png)

12. **Update the Source Files query**  
    Click the gear icon next to the last Navigation step and select the **Files** folder in the Lakehouse you created earlier.

    ![Navigation Settings](../assets/img/navigation_settings.png)
    ![Change Lakehouse](../assets/img/change_lakehouse.png)

13. **Add a Default Data Destination**  
    Bind the tables as shown in the screenshot below.

    ![Bind Tables](../assets/img/bind_tables.png)

14. **Publish the dataflow.**

15. **Generate a Semantic Model**  
    In the Lakehouse, click **New semantic model**, select your tables, and click **Create**. Name the new model **direct lake demo**.

    ![New Semantic Model](../assets/img/new_semantic_model.png)
    ![Select Tables](../assets/img/select_tables.png)

16. **Open Model view**  
    Create 1‑many relationships to match the screenshot below.

    ![Semantic Model Relationships](../assets/img/semantic_model.png)

17. **Use Copilot to create a report**  
    Prompt:  
    `"Create me a report to show sales over time including both high-level and detailed information."`

    ![Copilot Report Creation](../assets/img/copilot_report_creation.png)

---

## Reflection

- **Checkpoint:** Review your Lakehouse, Dataflow, and Semantic Model with your group.  
- **Discuss:** What worked well? Where did you encounter challenges?  
- **Prepare:** Bring your questions and findings to the next session.

---

**Tips for Success:**
- If you get stuck, ask your instructor or a classmate for help.
- Pause at checkpoints to review your progress.
- Share your screen if you need troubleshooting assistance.

---

Let your instructor know if you need further clarification or support!