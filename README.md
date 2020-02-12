# 2illow Graph CRUD API
## Create
**Endpoint: /api/graphs/:id (POST)**

## Read
**Endpoint: /api/graphs/:id (GET)**

**Legacy endpoint: /seed (GET)**
sample data:
```
[ { graphData: 
   { city: 
      { price: [120 length array],
        name: 'San Francisco' },
     neighborhood: 
      { price: [120 length array],
        name: 'Marina' },
     property: 
      { price: [120 length array],
        sold: [ 956341, 34 ],
        name: '531 Kirkham St, San Francisco, CA 94122' 
      } 
   },
  _id: 5e4456e3b4798a40248be9e2,
  id: 0,
  zestimate: '$1,225,583',
  updateZestimate: 'https://www.zillow.com/sellerlanding/edityourhome/0',
  salesRange: '$1.10M - $1.34M',
  __v: 0 
} ]
```
## Update
**Endpoint: /api/graphs/:id (PATCH)**

## Delete
**Endpoint: /api/graphs/**

