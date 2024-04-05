## Requisitos
- NPM;
- Node;

## HTTP

### GET `/prompts`

Fetches a list od prompts from DB

#### Response body

```json
{
 "promtps": [
   "id": "string",
  "title": "string",
  "template": "strnig"
]
}
```
### POST `/videos`

uplaod Videos

#### Request file
- FormResquest file

#### Response body

```json
{
 "video": {
    "id":"string",
    "name":"string",
    "path":"string",
    "createdAt":"string"
}
}
```

### POST `/videos/:videoId/transcription`

sendo video to create transcription

#### Request body

```json
{
 "promtp": "string"
}
```

#### Response body

```json
{
 "transcription": "string"
}
```

### POST `/ai/complete`

generates ai response

#### Request body

```json
{
 "videoId": "string",
 "promtp": "string",
 "temperature": "number",

}
```

#### Response body

Open ai Chat Response
