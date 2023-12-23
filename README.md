---
title: test
app_file: main.py
sdk: gradio
sdk_version: 4.11.0
---
## 📰 News & Weather App

....

AI-Agent powered by the Chat Language Models from OpenAI's GPT-3 API.

![ChatBot Demo](img/chatbot.gif)

## Set up API KEY

- [OpenAI](https://platform.openai.com/account/api-keys)

- [OpenWeatherMap.org](https://platform.openai.com/account/api-keys)

- [Tavily Client](https://app.tavily.com/home)

You may encounter errors if you exceed the rate limit of the API. Go to your account[https://platform.openai.com/account/rate-limits] to increase your rate limit.

```
RateLimitError: Error code: 429 - {'error': {'message': 'Rate limit reached for gpt-3.5-turbo-1106 in organization org-CgCPLNbvA8MZmigOt11yoAP8 on requests per min (RPM): Limit 3, Used 3, Requested 1. Please try again in 20s. Visit https://platform.openai.com/account/rate-limits to learn more. You can increase your rate limit by adding a payment method to your account at https://platform.openai.com/account/billing.', 'type': 'requests', 'param': None, 'code': 'rate_limit_exceeded'}}

```

`pip install sentence-transformers`

## Start Streamlit app:

`streamlit run app.py`
