# LogisticService

The logistic service is published to your app specifically. The intention is for it to handle **hooks** on the various events that occur within your store purchase flow. The `LogisticService` handles the following events:

```php
shipping($user)
getTaxPercent($user)
afterPurchase($user, $transaction, $cart, $result)
afterSubscription($user, $plan)
afterRefundRequest($transaction)
afterRefund($transaction)
cancelSubscription($user, $plan)
afterPlaceOrder($user, $transaction, $cart)
orderCreated($order)
shipOrder($order)
cancelOrder($order)
```
