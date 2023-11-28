## PROBLEM STATEMENT
Utilize machine learning regression models to mitigate skewness and noise in copper industry data, employing normalization, scaling, and outlier detection. Additionally, create a lead classification model categorizing leads as Success (WON) or Failure (LOST) to enhance lead capture efficiency.
## ABOUT THE DATA
## ID
Column likely acts as unique identifier for tracking transactions/items.
## ITEM_DATE
Column crucial for tracking transaction/item dates, essential for business timing.
## QUANTITY TONS
Column signifies item quantity in tons for inventory and sales tracking.
## CUSTOMOR
"Customer column: Identifies buyers, vital for sales tracking and relationships."
## COUNTRY
"Country column informs customer locations, aiding logistics and international sales."
## STATUS
"Status column tracks transaction progress, from Draft to Won."
## ITEM TYPE
Column classifies item types for inventory and business reporting purposes.
## APPLICATION
The "application" column defines the specific use or application of the items. This information can help tailor marketing and product development efforts.
## THICKNESS
The "thickness" column provides details about the thickness of the items. It's critical when dealing with materials where thickness is a significant factor, such as metals or construction materials.
## WIDTH
"Width column details item sizes, crucial for product dimensions."
## MATERIAL_REF
Column tracks material source and composition, crucial for product identification.
## PRODUCT_REF
"product_ref" identifies and catalogues products in a standardized manner.
## DELIVERY DATE
This column records the expected or actual delivery date for each item or transaction. It's crucial for managing logistics and ensuring timely delivery to customers.
## SELLING PRICE
"Selling_price crucial for revenue and profitability analysis in sales data."
## APPROACH
## 1. DATA UNDERSTANDING
Identify variable types, remove '00000' in Material_Reference, treat as categorical.
## 2. DATA PREPROCESSING
Handle missing values, outliers, skewness; encode categoricals for robust ML preprocessing.
## 3. EDA
Visualize outliers and skewness with Seaborn: boxplot, distplot, violinplot.
## 4. FUTURE ENGINEERING
Engineer new features; drop correlated columns using heatmap for optimization.
## 5. MODEL BUILDING AND EVALUATION
Split data, train various classifiers, optimize, and evaluate for classification/regression.
## 6. STREAMLIT GUI
Streamlit GUI: Input task (Regression/Classification), column values; predict, display output.
