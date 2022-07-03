# Cash-Flow-analysis-and-forecasting is a functioning Excel-based scalable and flexible BI template. To use this model please copy the folder "Cash_BI" to your disk C root directory and feel free to open Cash_BI.xlsm and explore analytical data on different Excel sheets.
All numbers are test data, are not trade secret and are therefore not subject to any view restriction. This model uses three sources of information:
- Transactional data (tblMain.xlsm):  aggregated data from an ERP-system (for example, Excel-format extract from SAP ERP)
- Liquidity forecast (tblExtra.xlsm): data collected in Excel from Funds Centers (based on SAP ERP Funds Reservation documents)
- Planning data (tblPlan.xlsm):       data calculated from Cash Flow budget statement (Cash_From_Budget.xlsx)
Data files are processed in MS Access file (Cash_BI.accdb) using SQL, data consistency is checked within data files using Excel formulas and Visual Basic code in Excel Macros.
Cash Flow analysis is performed in the file Cash_BI.xlsm using different instruments and methods (Pivot Tables, formulas-based analytical tables, Cash Flow forecast plots and KPIs) and summarizes all information.
