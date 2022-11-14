# sort by products id = [
  8,9,7,6,5,4,1,2,3,0,
]

```JSON
[
  {
    "id": 1,
    "name": "family 1",
    "products": [
      {
        "id": 0,
        "name": "product 0"
      },
      {
        "id": 1,
        "name": "product 1"
      },
      {
        "id": 2,
        "name": "product 2"
      },
      {
        "id": 3,
        "name": "product 3"
      }
    ]
  },
  {
    "id": 2,
    "name": "family 2",
    "products": [
      {
        "id": 4,
        "name": "product 4"
      },
      {
        "id": 5,
        "name": "product 5"
      },
      {
        "id": 6,
        "name": "product 6"
      }
    ]
  },
  {
    "id": 3,
    "name": "family 13",
    "products": [
      {
        "id": 7,
        "name": "product 7"
      },
      {
        "id": 8,
        "name": "product 8"
      },
      {
        "id": 9,
        "name": "product 9"
      }
    ]
  }
]
```


# sort by users id = [
  8,9,6,4,99,12,66,67,2,1,32,55,5,7,91,9
]

```JSON
[
  {
    "id": 1,
    "name": "user 1",
  },
  {
    "id": 32,
    "name": "user 32",
  },
  {
    "id": 2,
    "name": "user 2",
  },
  {
    "id": 67,
    "name": "user 67",
  },
  {
    "id": 4,
    "name": "user 4",
  },
  {
    "id": 12,
    "name": "user 12",
  },
  {
    "id": 9,
    "name": "user 9",
  },
  {
    "id": 99,
    "name": "user 99",
  },
]
```


# merge and remove

```JSON
[
  {
    'id': 1,
    'name': 'sale 1',
    'products': [8,1,44,12,42,3,23,7],
    'groups': [1,2],
  },
  {
    'id': 2,
    'name': 'sale 2',
    'products': [23,77,99,42,12,7,8,72,1,33,74,55],
    'groups': [1],
  },
]
```

```JSON
[
  {
    'id': 1,
    'products': [1,12,8,33,72,44],
  },
  {
    'id': 2,
    'products': [23,15,3,99,42,75],
  },
]
```
