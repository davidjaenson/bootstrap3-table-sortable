# bootstrap3-table-sorter
A very simple table sorting plugin for bootstrap 3 (requires glyphicons and JQuery)


To use simply include the script and add the table-sortable class to your table.

If you wish to disable the sorting of certain columns add the data-table-sortable-disable attribute to that column's header cell (the th-tag).

For example:
```html
<table class="table-sortable">
    <thead>
        <tr>
            <!-- We disable sorting by id-->
            <th data-table-sortable-disable>#id</th>
            <th>Name</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>John Doe</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Jane Doe</td>
        </tr>
    </tbody>
</table>
```


If you wish to set a table as sortable via Javascript, simply do the following:
```js
$("table i want to make sortable").tableSortable();
```
