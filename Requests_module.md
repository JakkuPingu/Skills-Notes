# Requests Module

## Steps for GET request

```
$ import Requests

$ URL = "Enter URL here"

$ r = requests.get(URL)

$ print(r.text)
```

## Changing Headers

```

Example used is User-Agent
$ headers = {"user-agent": "Googlebot/2.1"}

$ r = requests.get(URL, headers=headers)

$ print(r.text)
```

## Changing Params

```
$ payloads = {"Example Payload": "Example value"}

$ r = requests.get(URL, params=payloads)

$ print(r.text)
```

## Using params in POST

```
$ payloads = {"Example Payload": "Example value"}

$ r = requests.post(URL, data=payloads)

$ print(r.text)
```

## Steps for Json request

```
URL must have Json

$ print(r.json())
```
