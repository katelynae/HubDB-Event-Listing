![HubSpot](https://cdn2.hubspot.net/hubfs/327485/HubSpot%20Wordmark%20-%20Full%20Color.png "HubSpot")
## Code Gallery

---

# Module - HubDB Event Listing w/ Dynamic Pages
This module is intended to be used with [HubSpot's HubDB tool](https://designers.hubspot.com/docs/tools/hubdb) to create a listing section for events. Each event card can also link to it's own event details page using [HubDB Dynamic Pages](https://designers.hubspot.com/docs/tutorials/how-to-build-dynamic-pages-with-hubdb).


## How to use this module

Before using this module you must create a HubDB table first to store your event listing information. Instructions on how to create and edit a HubDB table can be found [here](https://knowledge.hubspot.com/articles/kcs_article/cos-general/how-to-edit-hubdb-tables).

### Step 1 - Create HubDB table

In order for the HubL contained within this module to work correctly the HubDB table must contain the following columns, column names must match exactly:

| Column Label        	 | Column Name           | Column Type   |
| ------------------- 	 |:---------------------:| ------------: |
| Name                	 | name                  | text          |
| Date				  	 | date 				 | date 		 |
| Region 			  	 | region 				 | text 		 |
| Image 			  	 | image 				 | image 		 |
| Description 		  	 | description 		  	 | rich text 	 |
| Agenda 			  	 | agenda 				 | rich text 	 |
| Featured Speaker Image | speaker_image 		 | image 		 |
| Featured Speaker Bio   | speakers 			 | rich text 	 |


### Step 2 - Allow use of Dynamic Pages

In order to use the HubDB Dynamic Pages in this module this option must be toggled on within your HubDB table settings. See screenshot below:

![alt text]( https://github.com/katelynae/HubDB-Event-Listing/screenshots/2-table-settings.png "HubDB table settings")

### step 3 - Place on any HubSpot CMS Page

Once you have your table created and this module downloaded into your design manager you can place the module on any HubSpot template or page. Choose the HubDB table data you wish to use with the module by selecting the 'HubDB Table' module field.


