# Supeset User Interface Design

## API 返回的 JSON 对象 JSON Objects returned by API:

确保正确的内容类型，例如 `Content-Type: application/json; charset=utf-8` 已正确返回。

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

### 获取自身信息 GetMyself

`POST /api/user/current`

Authentication required, returns a [UserProfileResponse](#userprofileresponse)
