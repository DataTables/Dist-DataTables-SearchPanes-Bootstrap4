# SearchPanes for DataTables with styling for [Bootstrap4](https://getbootstrap.com/docs/4.6/getting-started/introduction/)

This is the distribution package for the [SearchPanes extension](https://datatables.net/extensions/searchpanes) for [DataTables](https://datatables.net/) with styling for [Bootstrap4](https://getbootstrap.com/docs/4.6/getting-started/introduction/).

The SearchPanes extension for DataTables provides improved Searching functionality allowing users to select options from a "Pane" which will then in turn search the DataTable and return the relevant results. There are multiple configuration options available to enhance SearchPanes.


## Installation

### Browser

To use DataTables with a simple `<script>` tag, rather than using this package, it is recommended that you use the [DataTables download builder](https://datatables.net/download) which can create CDN or locally hosted packages for you, will all dependencies satisfied.

### npm

For installation via npm, yarn and other similar package managers, install this package with your package manager - e.g.:

```
npm install datatables.net-bs4
npm install datatables.net-searchpanes-bs4
```

Then, to load and initialise DataTables and SearchPanes in your code use:

```js
import DataTable from 'datatables.net-bs4';
import 'datatables.net-searchpanes-bs4';

new DataTable('#myTable', {
    layout: {
        top: 'searchPanes'
    }
});
```


## Documentation

Full documentation and examples for SearchPanes can be found [on the DataTables website](https://datatables.net/extensions/searchpanes).

## Bug / Support

Support for DataTables is available through the [DataTables forums](https://datatables.net/forums) and [commercial support options](https://datatables.net/support) are available.


## License

This software is released under the [DataTables Plus License](https://datatables.net/license/plus). To use the software a license key must be applied - see [DataTables Plus](https://datatables.net/plus).

