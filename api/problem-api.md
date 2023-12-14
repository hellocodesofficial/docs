---
description: 문제 API
---

# Problem API

{% swagger method="get" path="" baseUrl="https://hellocodes.kro.kr/api/problem/:id" summary="" %}
{% swagger-description %}
:id = 문제 id
{% endswagger-description %}

{% swagger-response status="200: OK" description="" %}
```json
{
  “code”: 200,
  “message”: ‘성공‘,
  “data”: {
    
  }
}
```
{% endswagger-response %}

{% swagger-response status="404: Not Found" description="" %}
```json
{
  “code”: 404,
  “message”: ‘[에러 메시지]‘
}
```
{% endswagger-response %}
{% endswagger %}
