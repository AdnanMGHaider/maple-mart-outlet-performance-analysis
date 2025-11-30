# Maple Mart Dataset

## Data Dictionary

This data dictionary describes all fields in the cleaned dataset stored in `data_clean/MapleMart_Complete_Analysis.xlsx`.

| Column Name               | Description                                                                                                                       | Example Value         | Type        |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ----------- |
| Item Fat Content          | Fat profile of the product. Standardized to Low Fat and Regular                                                                   | Low Fat               | Categorical |
| Sr. no                    | Sequential row number added for counting items per outlet                                                                         | 142                   | Integer     |
| Item Identifier           | Unique code assigned to each product SKU                                                                                          | FDX32                 | Text        |
| Item Type                 | Product category assigned by Maple Mart                                                                                           | Fruits and Vegetables | Categorical |
| Outlet Establishment Year | The year the fulfillment outlet began operations                                                                                  | 2018                  | Integer     |
| Outlet Identifier         | Unique code assigned to each physical outlet                                                                                      | OUT027                | Text        |
| Outlet Location Type      | Internal tier classification of Canadian trade areas. Tier 1: **Urban core**, Tier 2: **Mid sized**, Tier 3: **Emerging markets** | Tier 3                | Categorical |
| Outlet Size               | Operational capacity of an outlet based on floor space **Small**, **Medium**, **High**                                            | Medium                | Categorical |
| Outlet Type               | Store format used by Maple Mart. Includes Supermarket Type1, Type2, Type3 and Grocery Store                                       | Supermarket Type1     | Categorical |
| Item Visibility           | Relative prominence of the item either in store or in app search results                                                          | 0.0258                | Decimal     |
| Item Weight               | Weight of the item’s package in kilograms                                                                                         | 13.85                 | Decimal     |
| Total Sales               | Revenue generated from this product line item. Values are treated as CAD                                                          | 145.4786              | Decimal     |
| Rating                    | Customer rating on a five point scale                                                                                             | 5                     | Integer     |
