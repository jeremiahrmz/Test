Case Study B: Enhanced Asset Reconciliation
============================================

This ZIP file contains all materials required for Case Study B submission.

Files Included:
---------------
1. Output_Correct_asset_inventory.csv — Final validated inventory with asset type, IP, OS, etc.
2. Output-Corrections-List_servers.csv — Server records flagged for removal.
3. Correction-List_workstations.csv — Workstations not found in AD/Scanner.
4. Outpout-Corrections-IP_tracker.csv — IP entries with no associated active asset.
5. Corrections_AD.csv — Assets discovered by scanner but missing in AD (suggest add).
6. asset_reconciliation.py — Python script for reconciliation.
7. README.txt — This instruction file.

How to Use:
-----------
- Open asset_reconciliation.py in VS Code or any Python IDE.
- Ensure pandas and openpyxl are installed (`pip install pandas openpyxl`).
- Place CaseStudy-B-IT_Asset_management.xlsx in the same folder.
- Run the script to regenerate outputs.
- Review the generated CSVs.
