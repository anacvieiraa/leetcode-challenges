## 💡 Solution Logic

To solve this problem, we need to find products that are both **low in fat** and **recyclable**.

The `Products` table contains the following relevant columns for this check:

- `low_fats`: indicates whether the product is low in fat (`'Y'` or `'N'`)
- `recyclable`: indicates whether the product is recyclable (`'Y'` or `'N'`)

The logic of the query is straightforward:
- Filter all records where `low_fats = 'Y'` **and** `recyclable = 'Y'`

In other words, we should return only the products that satisfy **both conditions at the same time**.


