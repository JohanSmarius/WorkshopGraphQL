```graphql
query ordersContainingMore5Items {
  orders(where : {  orderLines:  {
      all:  {
          quantity:  {
            gt: 5
          }
      }
    } }) {
  ...orderInfo
  }
}
```