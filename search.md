# Elasticsearch

- Query by URL
- Query by DSL
  - Term query
  - Match query
  - Boolean field query
  - Term multiple query
  - Ids query
  - Range query
  - Non-null
  - Prefix query
  - Wildcard
  - Full text query (match query)
    `match query`, `match query boolean operator`, `multi_match`
  - Multiple query with boolean logic
  - Filter
  - must_not operator
  - should operator

# QEURY BY URL

```javascript
// GET product/default/_search?q=*
// GET product/default/_search?q=name:Lobster
// GET product/default/_search?q=tags:Meat
```

# QUERY BY DSL
