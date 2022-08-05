---
stoplight-id: sp3j07nbt9rw3
---

# Overview

This API translates a string between two specified languages.

Calling the API with Text: "Hello" and a TargetLanguageCode of `ja` (for Japanese) as follows:

```
curl --request GET --url 'http://localhost:8080/api/translatetext?TargetLanguageCode=ja&Text=Hello' --header 'Content-Type: application/json' --header 'apiKey: T....0'
```

results in the following response:

```javascript
{
  "TranslatedText": "こんにちは",
  "SourceLanguageCode": "en",
  "TargetLanguageCode": "ja"
}
```
