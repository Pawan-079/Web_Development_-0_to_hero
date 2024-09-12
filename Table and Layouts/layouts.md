Layouts
HTML uses different tags to create and style layouts. Two common tags for grouping elements are <div> and <span>.

1. Grouping Elements: <div> Tag
The <div> tag is a block-level element used to group other HTML elements and apply styling or layout.

html
Copy code
<div style="background-color: lightblue; padding: 20px;">
    <h2>Section Title</h2>
    <p>This is a paragraph inside a div element. Divs are used for layout and styling.</p>
</div>
Block-level element: Takes up the full width available.
Can be styled using CSS to create sections or containers.
2. Grouping Elements: <span> Tag
The <span> tag is an inline element used to group parts of text or other inline elements for styling or scripting.

html
Copy code
<p>This is a paragraph with <span style="color: red;">highlighted text</span> inside it.</p>
Inline element: Does not break the flow of content.
Useful for styling or targeting small portions of text.
Full Example
Here’s a complete example combining tables and layout tags:

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tables and Layouts</title>
    <style>
        .container {
            width: 80%;
            margin: 0 auto;
        }
        .highlight {
            color: red;
            font-weight: bold;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            text-align: left;
            border: 1px solid #ddd;
        }
        th {
            background-color: #f4f4f4;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Data Table</h1>
        <table>
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

        <h2>Layout Example</h2>
        <div style="background-color: lightblue; padding: 20px;">
            <h2>Section Title</h2>
            <p>This is a paragraph inside a div element. Divs are used for layout and styling.</p>
        </div>

        <p>This is a paragraph with <span class="highlight">highlighted text</span> inside it.</p>
    </div>
</body>
</html>
This example showcases a data table and demonstrates how to use <div> and <span> for layout and styling purposes.