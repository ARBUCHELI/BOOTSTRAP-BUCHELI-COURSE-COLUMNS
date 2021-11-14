# BOOTSTRAP-BUCHELI-COURSE-COLUMNS

We’ve covered containers and rows, now we have to go one level deeper and explore Bootstrap’s columns.

Columns are the immediate children of rows and store content. By default, a column will take up the entire width of its parent row. As we add more columns inside a row, the default behavior is for each column’s width to be readjusted to fit in the row — each column will have the same width. At most, a row will accommodate 12 columns. Study the diagram below to see how column sizing works:

![](https://content.codecademy.com/courses/learn-bootstrap-4/simple-12-grid.svg)

Notice the first row in the diagram has 1 column and it takes up the entire width of the row. We could say that this column takes up the width of 12 individual columns. The width of an individual column can be seen in the last row of the diagram.

To create a column, we assign an element with the class of "col". Take a look at the provided example with a container that has a nested row which has a nested column:

```
<div class="container">
  <div class="row">
    <div class="col">
    </div>
  </div>
</div> 
```

## Take a look at the live example here:
https://bucheli-web-development-bootstrap-course-columns.netlify.app/
