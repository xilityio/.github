# Observability made simple

## Xility is a low-code observability platform for software products
We help you improve your product with data and ensure it is always online.
Start collecting metrics, registering events and fire alerts with few lines of code:

```javascript
const xility = require("xility").start(token)

xility.send_metric({"name": "subscription", "value": 1})
xility.send_event({"name": "Service successfully deployed"})
xility.alert("Wissman score above 5.2")
```
