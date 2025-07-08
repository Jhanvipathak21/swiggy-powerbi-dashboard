# swiggy-powerbi-dashboard
End-to-end Power BI dashboard project using Swiggy restaurant dataset, with full data cleaning, DAX, and report visuals.
## 🛠️ Technologies Used
- Power BI
- Power Query (M language)
- DAX
- SQL (if used for data exploration)



References for notes:- 

1. Merge query:- (https://learn.microsoft.com/en-us/power-query/merge-queries-overview )
3. Data table:-  ( https://learn.microsoft.com/en-us/dax/datatable-function-dax )
4. Unpivot columns:- (https://support.microsoft.com/en-us/office/unpivot-columns-power-query-0f7bad4b-9ea1-49c1-9d95-f588221c7098)


**FOR CREATING TABLE**
Rank Table = 
DATATABLE(
    "sort", INTEGER,
    "Type", STRING,
    "No", INTEGER,
    {
        {0, "Default", 0},
        {1, "Top 5", 5},
        {2, "Top 10", 10},
        {3, "Top 20", 20},
        {4, "Top 30", 30},
        {5, "Top 100", 100}
    }
)

![image](https://github.com/user-attachments/assets/1b8c72e0-b079-48a5-b1e0-0dc2d1fda024)

