# Supeset Login Interface Design

## API 返回的 JSON 对象 JSON Objects returned by API:

确保正确的内容类型，例如 `Content-Type: application/json; charset=utf-8` 已正确返回。

### TokenResponse (for authentication)

用于获取 token 与 refreshToken

```JSON
{
  "id": 1,
  "token": "jwt.token.here",
  "refreshToken": "rjwt.token.here",
  "expiresIn": 1000
}
```

### UserProfileResponse

用于获取登录用户基本信息

```JSON
{
  "id": 1,
  "username": "supeset",
  "bio": "I work at statefarm",
  "avatar": "https://static.productionready.io/images/smiley-cyrus.jpg",
}
```

## 终端接口 Endpoints:

### 登录 Login

`POST /api/token/login`

Example request body:

```JSON
{
 "username": "supeset",
  "password": "supeset"
}
```

No authentication required, returns a [TokenResponse](#tokenresponse-for-authentication)

Required fields: `username`, `password`

### 注册 Registration:

`POST /api/token/register`

Example request body:

```JSON
{
  "username": "supeset",
  "password": "supeset"
}
```

No authentication required, returns a [TokenResponse](#tokenresponse-for-authentication)

Required fields: `username`, `password`

## 维持登录 RefreshToken

Example request body:

```JSON
{
  "refreshToken": "rjwt.token.here",
}
```

No authentication required, returns a [TokenResponse](#tokenresponse-for-authentication)

Required fields: `refreshToken`
