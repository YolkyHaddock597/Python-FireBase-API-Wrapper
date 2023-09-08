# Python-FireBase-API-Wrapper
[![Python application](https://github.com/YolkyHaddock597/Python-FireBase-API-Wrapper/actions/workflows/main.yml/badge.svg)](https://github.com/YolkyHaddock597/Python-FireBase-API-Wrapper/actions/workflows/main.yml)


WORK IN PROGRESS

This is a basic wrapper for the auth parts of the api. This is not intended to be a full solution for the firebase api.



```python
import firebase_api

config = None

firebase = FireBaseInit(info, config)

auth = firebase.auth()

user = auth.sign_in_with_email_and_password("EMAIL", "PASSWORD")
```
