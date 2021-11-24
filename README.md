# OneClickEvent.app docs


## How to make a request


Request method: **POST**

Url: https://hook.integromat.com/58bailvfca7xawk7x4d0a1x52t4d9tgd

**Example request**
```
{
    "start_date": "20211206T090000",
    "end_date": "20211206T110000",
    "title": "Best tools for e-mail marketing",
    "description": "At this weekly meeting we are going to talk about tools for e-mail marketing",
    "location": "https://us04web.zoom.us/j/76984884816?pwd=aWpvSlJQbmI0ZjRadkl5ZklHa2FjUT09",
    "timezone": "Europe/Warsaw",
    "api_key": "your-api-key"
}
```

The `start_date` and `end_date` parameters must be in [ISO format](https://en.wikipedia.org/wiki/ISO_8601): `YYYY-MM-DDThh:mm:ss`. The delimiters can be omitted.
