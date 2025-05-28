```graphql
query {
  allOrders {
      id
      customer {
        name
      }
      orderStatus
      orderTime
      orderLines {
        product {
          name
        }
      quantity
    }
  }
}
```