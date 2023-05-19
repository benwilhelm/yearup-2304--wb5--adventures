This repo includes two JS files, representing slightly
different ways to solve the exercise.

## `scripts/index.js`

This is the end result of the demo that I did in class.

This solution pulls the individual steps of clearing and writing the table rows into reusable functions, then uses those functions to create a function called loadTableRows.

By creating that reusable function, we can call it in multiple cases. First, we can use it on the initial page load (line 133) to load all of the activities into the table, then we can also use it in the change handler to load only the selected activities.

## `scripts/index-no-helpers.js`

This is a simplified solution that uses no helper functions, just puts all the filtering logic into the 'change' event handler of the select element
