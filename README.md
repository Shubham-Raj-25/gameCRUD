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

### Update game

```http
 PATCH /api/game/${id}
```
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of game to update |

### Delete game

```http
 DELETE /api/game/${id}
```
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of game to delete |

