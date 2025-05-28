```graphql
query allOrdersSortedDescendingOrderTime {
  orders(order: { orderTime: DESC}) {
    ...orderInfo
  }
}
```