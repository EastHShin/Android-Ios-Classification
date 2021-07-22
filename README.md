# Android-Ios Question Classification

---

## Overview

---
The Android-Ios Question Classification model takes questions as input.
It's a model that classify whether the question is about Android or Ios.

Github : [Github]()
<br>
Huggingface : [Huggingface]()
<br>
Workspace : [Workspace]()

## How to make

---

## How to run a Demo

---

#### Endpoint : 

## With CLI

---

### Post Parameter
```
question = "question about Smartphone"
```

### Input format
```
    {
        "question" : "string"
    }
```

### Output format
```
    {
        0: {'label': 'LABEL_0', 'score': score}
    }
```

### API Prediction Test

```
$ curl -X POST "https://main-android-ios-classification-east-h-shin.endpoint.ainize.ai/classification" -H "accept: application/json" -H "Content-Type: multipart/form-data" -F "question={I bought the GoodNote}"
{
    0: {'label': 'LABEL_1', 'score': 0.9959855079650879}
}
```

### Healthy Check

```
$ curl --request GET 'https://main-android-ios-classifcation-east-h-shin.endpoint.ainize.ai/healthz'
{
  Health
}
```
