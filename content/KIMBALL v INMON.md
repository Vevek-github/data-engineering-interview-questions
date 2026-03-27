+ Inmon follows a top-down approach. The organization first builds an Enterprise Data Warehouse (EDW)
   in a normalized 3NF structure, and then creates subject-specific data marts from it.

+ Kimball follows a bottom-up dimensional approach. The organization models data around business processes using 
 fact and dimension tables, and integrates these dimensional models using conformed dimensions.





| Feature           | Inmon                                     | Kimball                                        |
| ----------------- | ----------------------------------------- | ---------------------------------------------- |
| Approach          | Top-down                                  | Bottom-up                                      |
| First goal        | Enterprise Data Warehouse                 | Dimensional data marts                         |
| Core model        | Normalized 3NF                            | Star schema / dimensional model                |
| Integration style | Centralized EDW first                     | Conformed dimensions across marts              |
| Focus             | Enterprise-wide consistency               | Business usability and fast delivery           |
| Best for          | Strong governance and centralized control | Faster analytics delivery and easier reporting |
