# intro_to_json.json

- JSON or JavaScript Object Notation is a lightweight text-based open standard designed for human-readable data interchange.

  1. JSON stands for JavaScript Object Notation.
  1. The format was specified by Douglas Crockford.
  1. It was designed for human-readable data interchange.
  1. It has been extended from the JavaScript scripting language.
  1. The filename extension is .json.
  1. JSON Internet Media type is application/json.
  1. The Uniform Type Identifier is public.json.

### Expense tracker

* For Single Entity the following is the example to write JSON
```json
{
"Expense_id" : 1001, 
"Category" : "food",
"Amount" : 300, 
"Purpose" : "Cash", 
"Description" : "Icecream"
}
```

- For Multiple entities in JSON

```json
[
{"Expense_id" : 1001, "Category" : "food", "Amount" : 300, "Purpose" : "Cash", "Description" : "Icecream"},
{"Expense_id" : 1002, "Category" : "Travel", "Amount" : 3000, "Purpose" : "Online", "Description" : "Hyderabad"},
{"Expense_id" : 1003, "Category" : "Clothing", "Amount" : 4000, "Purpose" : "Online", "Description" : "Saree"},
{"Expense_id" : 1004, "Category" : "Shopping", "Amount" : 1000, "Purpose" : "Cash", "Description" : "Bangles"}
]
```

