# Good First Issues

## Add a Spanish keyword pack as an optional taxonomy
Scope: add an optional taxonomy JSON file with Spanish keyword rules and a test using synthetic Spanish complaints.
Good for a first contribution: keep the default taxonomy unchanged.

## Export the trend by month as CSV
Scope: add a download button that turns the theme by month data into a tidy CSV with theme, month and count columns.
Good for a first contribution: reuse the existing CSV escaping in src/logic.js.

## Let users mark a theme as not applicable per complaint
Scope: add a simple override control in the results table that removes a tag before download, and cover it with a logic test.
Good for a first contribution: keep overrides in page memory only.
