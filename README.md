# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1
use the image tag to upload the required photo by source attribute
## Step 2
Create a map name SEC,By using the shape attribute to select a particular place to show the information  
## Step 3
By using the coords attribute we can select a particular area we needed ,Then using the href the website is called to show the details.

# Code:
````
<img src="C:\Users\admin\Downloads\WhatsApp Image 2023-11-16 at 6.51.50 AM.jpeg"  alt="SAVEETHA ENGINEERING COLLEGE" usemap="#SEC">

<map name="SEC">
  <area shape="rect" coords="785,448,623,314" alt="INFORMATION TECHNOLOGY" href="file:///C:/Users/admin/Documents/web%20applications/MAP/IT.html">
  <area shape="rect" coords="86,241,0,46" alt="MECHANICAL DEPARTMENT" href="file:///C:/Users/admin/Documents/web%20applications/MAP/mech.html">
  <area shape="rect" coords="262,250,383,380" alt="ELECTRONICS-COMMUNICATION ENGINEERING" href="file:///C:/Users/admin/Documents/web%20applications/MAP/ece.html">
  <area shape="rect" coords="447,371,627,503" href="file:///C:/Users/admin/Documents/web%20applications/MAP/cse.html" alt="computer-science-engineering">
  <area shape="rect" coords="672,277,889,180" href="file:///C:/Users/admin/Documents/html%20aids/coding.html" alt="ARTIFICIAL INTELLICENCE AND DATA SCIENCE">
</map>

````
# Output:
![image](https://github.com/MARXINLIJO/Ex-04-webTech_imagemap/assets/145742540/99987728-1069-427f-967f-638d9fea2b6e)


# Result:
Thus the Program executed sucessfully
