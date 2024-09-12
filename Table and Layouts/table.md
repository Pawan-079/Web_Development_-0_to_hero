Here’s a detailed Markdown explanation for Tables and Layouts in HTML:

markdown
Copy code
## 4. Tables and Layouts

### **Tables**

Tables are used to display data in a structured format. HTML provides several tags to create and style tables.

#### **1. Creating Tables**

##### **`<table>` Tag**

The `<table>` tag defines the table and encloses all table elements.

```html
<table>
    <!-- Table content goes here -->
</table>
<tr> Tag
The <tr> tag defines a row in the table. It is used within the <table> tag.

html
Copy code
<table>
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
</table>
<th> Tag
The <th> tag defines a header cell in the table. It is typically used within the <tr> tag and is bold by default.

html
Copy code
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
</table>
<td> Tag
The <td> tag defines a standard data cell in the table. It is used within the <tr> tag to hold table data.

html
Copy code
<table>
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
</table>
Full Example
Here is an example of a simple table with headers and data:

html
Copy code
<table border="1">
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>City</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>John Doe</td>
            <td>30</td>
            <td>New York</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>25</td>
            <td>Los Angeles</td>
        </tr>
        <tr>
            <td>Mike Johnson</td>
            <td>35</td>
            <td>Chicago</td>
        </tr>
    </tbody>
</table>
<thead>: Groups header content.
<tbody>: Groups body content.
border="1": Adds a border to the table (for visual clarity).
