**Bug lists**

**ID 01. Sorting does not persist after page refresh**

**Steps to reproduce:**
1. Browse any category
2. Use sorting by name or price
3. Get the actual result
4. Refresh the page

**Actual result:**
- System show a message "no item found"

**Expected result:**
- After  refreshing user sees the correctly sorted items

**Attachments** [Vid01](https://drive.google.com/file/d/1y2Wnlvg3Si6LrkINLxl4C4IFjYwyxj14/view?usp=drive_link)

Related check-list item [#Product sorting](https://github.com/sv-serhii-qa/Portfolio-/blob/Marketpace-Volti/Functional%20check-lists.md)

**Severity** "Major"  
**Priority** "High"

**Environment** Chrome 144.0.7559.60, OS: Windows 11

------------------------------------------------------------------

**ID 02. Product | Logitech products are available in search results, but are not in the  
           manufacturer's catalog**

**Preconditions:**  - The user is already on Main page
                    -  Logitech products  ar exist in the catalog 
                    
**Environment:** Chrome 144.0.7559.60, OS: Windows 11


**Steps to reproduce:**           
1. Open search 
2. Search for “Logitech”
3. Verify that Logitech products are displayed
4. Open the catalog 
5. Use filter Manufacturer
6. Check the list to find “Logitech”
   
**Actual result:**
- Logitech does not exist in the list of manufacturers

**Expected result:**
- Logitech should  exist in the list of manufacturers, if their products  exist in the catalog and show in search results

**Severity** "Major"

**Priority** "Medium"

**Attachments:** [Pic1](https://drive.google.com/file/d/1c6YnGBTNqvMeGyZoXUghII4ydb2mQWtk/view?usp=drive_link) [Pic 2](https://drive.google.com/file/d/1KziLBYEZRIm7YRyaMtu5zX319EAx1U94/view?usp=drive_link)

**Notes** This issue was found through  exploratory testing without internal documentation.
 
