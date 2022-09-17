
# Youtube PlayList API

To show playlist video to your website


## API Reference

#### Get JSON

```http
  GET https://www.googleapis.com/youtube/v3/playlistItems
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get Video By Id

```http
  GET https://www.youtube.com/embed/videoid
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### To show video

Here using this javascript you can simply show your playlist
video on your website


## Deployment

To deploy by direct link

```bash
  https://youtube.googleapis.com/youtube/v3/playlistItems?part=snippet%2CcontentDetails&maxResults=[Numberofresultstoshow]&playlistId=[PlaylistIdhere]]&key=[YOUR_API_KEY]
```


## Features

- To Show video from PlayList
- Live Fetching
- Fullscreen mode
- Updated API V3

