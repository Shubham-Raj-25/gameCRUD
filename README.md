# gameCRUD

## API Reference
### Base API Endpoint
```
https://gamecrud-production.up.railway.app
```

#### Get all games

```http
  GET /api/game
```

#### Get game

```http
  GET /api/game/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of game to fetch |

#### Add game

```http
 POST /api/game
```
Schema to follow

| Parameter   | Type     | Description                       |
| :--------   | :------- | :-------------------------------- |
| `name`      | `string` | updated name of the game          |
| `url`       | `string` | updated url of the game           |
| `author`    | `string` | updated author of the game        |
| `date`      | `date`   | updated publish date of the game  |


### Update game

```http
 PATCH /api/game/${id}
```
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of game to update|

Schema to follow

| Parameter   | Type     | Description                       |
| :--------   | :------- | :-------------------------------- |
| `name`      | `string` | name of the game to add           |
| `url`       | `string` | url of game to add                |
| `author`    | `string` | author of the game to add         |
| `date`      | `date`   | publish date of the game to add   |

### Delete game

```http
 DELETE /api/game/${id}
```
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of game to delete |

