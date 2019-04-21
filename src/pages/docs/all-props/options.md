Options property could be given to component as `options` property. You can change behaviour of grid.

| Field                      | Type                   | Default       | Description                                                                       |
|:---------------------------|:-----------------------|:--------------|:----------------------------------------------------------------------------------|
| actionsColumnIndex         | number                 | 0             | Order of actions column                                                           |
| addRowPosition             | `first` or `last`      | `last`        | Position of add row                                                               |
| columnsButton              | boolean                | false         | Flag for columns button that controls which column could be rendered              |
| debounceInterval           | number                 | 200           | debounce interval for search and filter                                           |
| detailPanelType            | `single` or `multiple` | `multiple`    | Detail panel visibility type.                                                     |
| doubleHorizontalScroll     | boolean                | false         | Flag for double scroll bar for long tables                                        |
| emptyRowsWhenPaging        | boolean                | true          | Flag for rendering rows to complete page size                                     |
| exportButton               | boolean                | false         | Flag for export button that render export buttons                                 |
| exportDelimiter            | string                 | ,             | Delimiter to use in exported CSV file                                             |
| exportFileName             | string                 | Title         | Exported file name                                                                |
| exportCsv                  | func                   |               | Function to create a custom CSV file                                              |
| filtering                  | boolean                | false         | Flag for filtering row                                                            |
| header                     | boolean                | true          | Flag for header visibility                                                        |
| headerStyle                | object                 |               | Header cell style for all headers                                                 |
| loadingType                | `overlay` or `linear`  | `overlay`     | Loading animation type                                                            |
| maxBodyHeight              | number or string       |               | Max body height                                                                   |
| initialPage                | number                 | 0             | Initial Page Number                                                               |
| paging                     | boolean                | true          | Flag for paging feature                                                           |
| pageSize                   | numeric                | 5             | Number of rows that would be rendered on every page                               |
| pageSizeOptions            | array                  | [5, 10, 20]   | Page size options that could be selected by user                                  |
| paginationType             | `normal` or `stepped`  | `normal`      | Flag for pagination type                                                          |
| rowStyle                   | object or func         |               | Css style to be applied rows                                                      |
| showEmptyDataSourceMessage | boolean                | true          | Flag for showing message if there is no data in table                             |
| showSelectAllCheckbox      | boolean                | true          | Flag for showing select all checkbox                                              |
| search                     | boolean                | true          | Flag for search feature                                                           |
| searchFieldAlignment       | string                 | 'right'       | Alignment for search text field in toolbar                                        |
| searchFieldStyle           | object                 | {}            | Search field css style                                                            |
| selection                  | boolean                | false         | Flag for selection feature                                                        |
| sorting                    | boolean                | true          | Flag to activate or disable sorting feature of table                              |
| toolbar                    | boolean                | true          | Flag for toolbar                                                                  |
| showTitle                  | boolean                | true          | Flag for title                                                                    |
| toolbarButtonAlignment     | string                 | 'right'       | Alignment for buttons in toolbar                                                  |