# SearchPanes for DataTables with styling for [Bootstrap4](https://getbootstrap.com/docs/4.6/getting-started/introduction/)

This is the distribution package for the [SearchPanes extension](https://datatables.net/extensions/searchpanes) for [DataTables](https://datatables.net/) with styling for [Bootstrap4](https://getbootstrap.com/docs/4.6/getting-started/introduction/).

The SearchPanes extension for DataTables provides improved Searching functionality allowing users to select options from a "Pane" which will then in turn search the DataTable and return the relevant results. There are multiple configuration options available to enhance SearchPanes.


## Installation

### Browser

To use DataTables with a simple `<script>` tag, rather than using this package, it is recommended that you use the [DataTables download builder](//datatables.net/download) which can create CDN or locally hosted packages for you, will all dependencies satisfied.

### npm

For installation via npm, yarn and other similar package managers, install this package with your package manager - e.g.:

```
npm install datatables.net-bs4
npm install datatables.net-searchpanes-bs4
```

Then, to load and initialise the software in your code use:

```
import DataTable from 'datatables.net-bs4';
import 'datatables.net-searchpanes-bs4'

new DataTable('#myTable', {
    // initalisation options
});
```


## Documentation

Full documentation and examples for SearchPanes can be found [on the DataTables website](https://datatables.net/extensions/searchpanes).


## Bug / Support

Support for DataTables is available through the [DataTables forums](//datatables.net/forums) and [commercial support options](//datatables.net/support) are available.

### Contributing

If you are thinking of contributing code to DataTables, first of all, thank you! All fixes, patches and enhancements to DataTables are very warmly welcomed. This repository is a distribution repo, so patches and issues sent to this repo will not be accepted. Instead, please direct pull requests to the [DataTables/SearchPanes](http://github.com/DataTables/SearchPanes). For issues / bugs, please direct your questions to the [DataTables forums](//datatables.net/forums).


## License

This software is released under the [MIT license](//datatables.net/license). You are free to use, modify and distribute this software, but all copyright information must remain.

