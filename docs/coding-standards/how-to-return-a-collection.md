---
title: How to return a collection
description: Standards for manipulating resource collections
group: coding-standards
redirect_from: "/"
---

> The response **SHOULD** enclose the primary resource within a *data* object. Use the singular form of the resource name as the outer property name. 

```
GET /{base}/patients/9991234566
// 200 OK
Content-Type: application/json; charset=utf-8
{
  "data": {
    "patient": {
      "NHSNumber": "9991234566",
      "firstName": "Humphrey",
      "lastName": "Appleby",
      // ... other patient details ...
    }
  }
}
```

#TODO.
