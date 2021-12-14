# select
Bugfixed version of Tom Select v2.0.0

[Tom Select](https://github.com/orchidjs/tom-select) is an extensible and dynamic &lt;select&gt; UI control.
With autocomplete and native-feeling keyboard navigation, it's useful for tagging, contact lists, country selectors, and so on.
Tom Select was forked from [selectize.js](https://tom-select.js.org/docs/selectize.js/) with the goal of modernizing the code base, decoupling from jQuery, and expanding functionality.

I found [Tom Select](https://github.com/orchidjs/tom-select) when I was looking for a Javascript select library without jQuery ant React. Unfortunately, it was not modifying the original &lt;options&gt; list correctly, so I fixed the functionality.

## Usage
Import in your app:
```
@import "css/tom-select.css";
@import "css/tom-select.bootstrap5.css";
```
```
import TomSelect from 'js/tom-select.complete'
```
