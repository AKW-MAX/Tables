# HTML TABLES
Hello, today we are looking into HTML tables and to create them effectively. HTML tables allow developers to arrange data into rows and columns.
## **TABLE CELLS**
HTML tables consist of table cells inside rows and columns, each cell is defined a &lt;td&gt; and &lt;/td&gt; tag and everything between the tag is the content of a table cell. &lt;td&gt; stands for table data.
## **TABLE ROWS**
Each table rows starts with a &lttr&gt and ends with a &lt;/tr&gt; tag. &lt;tr&gt; tag stands for table rows. One can have as many rows as you want as long as the number of cells are the same in each row.
## **TABLE HEADER**
In a case when you need your cells to be table header cells we replace the &lt;td&gt; tag with the &lt;th&gt; tag and by default the &lt;th&gt;  elements are bold and centered but that can be changed using CSS.
## **TABLE GROUPING**
HTML tables can be divided into three parts &lt;thead&gt;, &lt;tbody&gt;, &lt;tfoot&gt;. This make easier to identify the various sections in your table for both the developers and the screen-crawlers, it also helps in styling using CSS.
**&lt;thead&gt;** tag is used to group the head part of your table while the **&lttbody&gt** is used to group the main content of the table. The **&lttfoot&gt** tag is used specify the footer part of the table. &lt;tbody&gt; tag is used as a child of the &lt;table&gt; element and after any &lt;caption&gt;, &lt;colgroup&gt; and &lt;thead&gt; element.
**&lt;caption&gt;** tag defines a table caption and it must be inseted immediately after the &lt;table&gt; element.
**&lt;colgroup&gt;** tag specifies a group of one or more columns in a table for formating. it is usefull for applying styles for each cell and for each row and it must be a child of the &lt;table&gt; element. 
**&lt;col&gt;** tag specifies column properties for each column within a &lt;colgroup&gt; elemen.
**span** attribute specifies the number of columns a &lt;col&gt; element should span
This is all about creating semantic HTML tables 
