# User Unsubscribed

### 

## Javascript Code
```js
window.appEventData098765 = window.appEventData098765 || [];
appEventData098765.push({
  "event": "User Unsubscribed",
    "subscription": {
        "subscriptionType": "<subscriptionType>",
        "unsubscribeMethod": "<unsubscribeMethod>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|subscriptionType|string|Describes the type of subscription. |news, updates, sales, events|||||||
|unsubscribeMethod|string|Describes the method used to unsubscribe.|footer field, registration opt in, order placed, notification preferences, ESP feed|||||||



