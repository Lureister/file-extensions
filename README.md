# Lurapi.Filext
An API of file extensions 📋

## Endpoints
### GET - /extensions.json
Returns the list of extensions.

```json
{
  "FileExtensions": [
    {
      "Name": ".323",
      "DisplayName": "H.323 Internet Telephony File",
      "Category": "text",
      "MimeType": "text/h323"
    },
    {
      "Name": ".3g2",
      "DisplayName": "3GPP2 Multimedia File",
      "Category": "video",
      "MimeType": "video/3gpp2"
    },
    {
      "Name": ".3gp",
      "DisplayName": "3GPP Media File",
      "Category": "video",
      "MimeType": "video/3gpp"
    }
  ]
}
```

## Data
### Categories

For the moment there are only these categories:

| Categories |
|------------|
| Video      |
| Audio      |
| Archive    |
| Text       |
| Other      |

## Contributing
Add the file extension in the array: 
```json
    {
      "Name": ".3gp",
      "DisplayName": "3GPP Media File",
      "Category": "video",
      "MimeType": "video/3gpp"
    }
```
Make a pull request.

That's all!
