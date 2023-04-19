# FSDB Project 1: E-commerce Data-Driven-Solutions Based on Kaggle Dataset: SALE REPORT

Dataset source: ![Kaggle Data Link](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data)

---

Data set has 9,272 rows and 7 columns. The figure below shows a sample of what the data in the first five rows were. The header title for the columns are 
* Index: starting from 0
* SKU code: Stocck keeping unit code
* Design no: design type
* Stock: how many of it is available
* Category: type of item
* Size: size of the item 
* Color: color of the item

<img src="https://user-images.githubusercontent.com/74875008/232811953-5eee9841-b126-4b0e-8dfd-483bd3ff7980.png" alt="Github" width="500" height="300"/>

---


### <span style="color:grey">Blanks And #REF

--- 

After going through the dataset, I noticed that there were some blank columns at the end and some of the columns had the #REF error in them and some of the had free written under the size column.
 
<img src="https://user-images.githubusercontent.com/74875008/232816378-da266c76-25f5-400c-83cd-e402ee37e6ce.png" alt="Github" width="500" height="300"/>

<img src="https://user-images.githubusercontent.com/74875008/232816871-4d0e54eb-e7ab-4bfa-b85c-7e9332f93eaa.png" alt="Github" width="500" height="300"/>

 
---

### <span style="color:grey"> Cleaned dataset
So I cleaned up the dataset by converting the portion of the file holding the data to a table with headers. I changed the font style and size them made the header to be bold so it would be easier to understand. I used the drop down arrowon the table header to fiilter out the blanks and errors.
 
<img src="https://user-images.githubusercontent.com/74875008/232810708-9d3c5d6c-ff6e-4538-83ea-88a61d4fa0a4.png" alt="Github" width="500" height="300"/>


---
### Header meanings

* **Index**: starting from 0. Just goes to show how the items were itemized and recorded.
* **SKU code**: Stocck keeping unit code which is a combination of the design no, size and color.
* **Design no**: design type. different items have different designs so similar designs where grouped.
* **Stock**: how many of it is available
* **Category**: type of item. The categories were as follows;
  * AN:Leggings 
  * Blouse
  * Bottom
  * Cardigan
  * Crop top
  * Crop top with palazzo
  * Dress
  * Jumpsuit
  * Kurta
  * Kurta set
  * Kurti
  * Lehenga Choli
  * Night wear
  * Palazzo
  * Pant
  * Saree
  * Set
  * Sharara
  * Skirt
  * Top
  * Top
* **Size**: size of the item. The sizes were as follows;
  * XS
  * S
  * M
  * L
  * XL
  * XXL
  * XXXL
  * 4XL
  * 5XL
  * 6XL
* **Color**: color of the item. The colors were as follows;
  * Aqua green
  * Beige
  * Black
  * Blue
  * Brown
  * Burgundy
  * Charcoal
  * Chiku
  * Coral
  * Coral orange
  * Coral pink
  * Cream
  * Dark blue
  * Dark green
  * Gold
  * Green
  * Grey
  * Indigo
  * Khaki
  * Lemon
  * Lemon yellow
  * Light blue
  * Light brown
  * Light green
  * Light pink
  * Light yellow
  * Lime green
  * Magenta
  * Mint
  * Mint green
  * Multicolor
  * Mustard
  * Navy
  * Off white
  * Olive
  * Olive green
  * Orange
  * Peach
  * Pink
  * Powder blue
  * Purple
  * Red
  * Rust
  * Sea green
  * Sky blue
  * Taupe
  * Teal
  * Teal blue
  * Teal green
  * Turqoise
  * Turqoise blue
  * Turqoise green
  * White
  * Wine
  * Yellow
 
---
