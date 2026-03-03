The JSON Query Tool is a self-contained React web application that lets you load, search, filter, and clean JSON data — all in the browser, with no backend required.
Built for production workflows: upload your JSON, find exactly the records you need, mark them for removal, and download a clean updated file ready to use.

Key Features

Search & Filter
▸	Search by key name, value, or both simultaneously
▸	5 match types: Contains  Exact Match  Is Null  Is Not Null  Key Exists
▸	Configurable search depth — all levels or limit to depth 1/2/3
▸	Case-sensitive or case-insensitive toggle

Results Management
▸	Every match shown with its full JSON path
▸	Individually mark / unmark records for removal
▸	Select All / Clear All shortcuts
▸	Option to remove the entire parent object instead of just the matched key

Output & Export
▸	Live preview of the cleaned JSON
▸	One-click copy to clipboard
▸	Download as .json file
▸	Load output back as new input for chained operations
▸	File size comparison: original vs updated

Usage Tips:

▸	To find all null values in a specific key (e.g. value2), set Key = value2, Match Type = Is Null.
▸	Use Key Exists match type with a key name to find all objects that contain that key, regardless of its value.
▸	Enable "Remove entire parent object" to delete the whole containing record (e.g. the full column object) instead of just the matched key.
▸	Chain operations: after removing records, click "Use as New Input" to run a second search on the cleaned data.
▸	The Search Depth selector is useful for large JSON files — restrict to depth 2 or 3 to speed up traversal and reduce noise.
