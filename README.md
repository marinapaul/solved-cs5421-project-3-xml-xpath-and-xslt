Download Link: https://assignmentchef.com/product/solved-cs5421-project-3-xml-xpath-and-xslt
<br>
Download the XML document TPCC.xml from “Files &gt; Project 3: XML, XPath and XSLT”.

The document’s root element is warehouses. Each warehouse record is represented by an element warehouse that is a sub-element of warehouses. There might be no warehouse. Each warehouse element consists of a sequence of four sub-elements: id, name, address, and items corresponding to the five attributes of the warehouse record. The address element consists of three sub-elements street, city and country. The items element contains one sub-element item for each of the items stocked in the warehouse. There might be no item in the warehouse. Each item element consists of a sequence of five sub-elements: id, im id, name, price, and qty. The first four sub-elements correspond to the four attributes of the item record and the qty element represents the quantity of that item stocked in the warehouse.

<h1>Question 1</h1>

Add an internal DTD to TPCC.xml. Make the DTD as tight as possible. It should validate this document and documents following the same design logic and it should not validate documents not following the same design logic. Validate the XML document with its DTD using XML copy editor.

Submit the revised file TPCC.xml containing the DTD .

<h1>Question 2</h1>

Write a separate XPath query for each of the following queries.

The queries should work for other similar documents (namely other documents following the same design logic).

Prefer the full syntax to the shorthand syntax.

Prefer a complete path to a concise path.

Submit your two XPath answers in the files query2a.txt and query2b.txt, respectively.

<table width="633">

 <tbody>

  <tr>

   <td width="616">(a) For each warehouse in Singapore, list the items that are available in the warehouse in quantity larger than 975. The result should return several &lt;item&gt; elements.</td>

   <td width="17">(2)</td>

  </tr>

  <tr>

   <td width="616">(b) Print the total quantity of items called “Sunscreen” available in Indonesia. The result should return a number.</td>

   <td width="17">(2)</td>

  </tr>

 </tbody>

</table>

<h1>Question 3</h1>

Consider the following query.

For each warehouse in Singapore or Malaysia, display the name of the warehouse and the name of the items available in the largest quantity in the warehouse.

Write a separate XSLT stylesheet for the query. The XSLT stylesheet must display the XML document as an HTML page presenting the result in a table or a list. You can debug and try the HTML generation with the XSLT stylesheet with XML copy editor. Alternatively, you can check the display with Firefox browser.

The XSLT stylesheet should work for other similar documents (namely other documents following the same design logic).

Prefer XSLT template matching with value-of and apply-template to imperative control structures (e.g. xsl:for-each).

Submit the XSLT file, query3.xsl.