# Notification Push API

## Update channel information

### `ANY` - /service/NotificationApiService/UpdateChannel

Use this request to update the channel information in redis from mongo database.


**Query Parameter(s)**:

| Parameter  | Type     | Description                             | Constraints           | Default | Required               |
| ---------- | -------- | --------------------------------------- | --------------------- | ------- | ---------------------- |
| `channel_id` | `string` | unique id for a channel               | N/A                   | N/A     | id is required        |

!!! note "Example"
    `service/NotificationApiService/UpdateChannel?channel_id=2`


**Request Body**: none


---

!!! success
    a return code is returned.

    **Status Code**: `200 OK`

    **Response Body**:

    ```json
    {
        "ret_code": <return code>,
    }
    ```

    | Key      | Type     | Description            |
    | -------- | -------- | ---------------------- |
    | `ret_code` | `int` | User ID                |


!!! failure "Bad Request"
    **Status Code**: `400 Bad Request`

    **Response Body**:

    ```json
    {
        "error": "<Error message>"
    }
    ```



[^_^]:
    end of a API end point









[^_^]:
    start of a API end point

## Update guild information

### `ANY` - /service/NotificationApiService/UpdateGuild

Use this request to update the guild information in redis from mongo database.



**Query Parameter(s)**:

| Parameter  | Type     | Description                             | Constraints           | Default | Required               |
| ---------- | -------- | --------------------------------------- | --------------------- | ------- | ---------------------- |
| `guild_id` | `string` | unique id for a guild               | N/A                   | N/A     | id is required        |

!!! note "Example"
    `service/NotificationApiService/UpdateGuild?guild_id=2`


**Request Body**: none


---

!!! success
    a return code is returned.

    **Status Code**: `200 OK`

    **Response Body**:

    ```json
    {
        "ret_code": <return code>,
    }
    ```

    | Key      | Type     | Description            |
    | -------- | -------- | ---------------------- |
    | `ret_code` | `int` | User ID                |


!!! failure "Bad Request"
    **Status Code**: `400 Bad Request`

    **Response Body**:

    ```json
    {
        "error": "<Error message>"
    }
    ```


[^_^]:
    end of a API end point



[^_^]:
    start of a API end point

## Update machine information

### `ANY` - /service/NotificationApiService/UpdateMachine

Use this request to update the machine information in redis from mongo database.


**Query Parameter(s)**:

| Parameter  | Type     | Description                             | Constraints           | Default | Required               |
| ---------- | -------- | --------------------------------------- | --------------------- | ------- | ---------------------- |
| `machine_id` | `string` | unique id for a machine               | N/A                   | N/A     | id is required        |

!!! note "Example"
    `service/NotificationApiService/UpdateMachine?machine_id=2`


**Request Body**: none


---

!!! success
    a return code is returned.

    **Status Code**: `200 OK`

    **Response Body**:

    ```json
    {
        "ret_code": <return code>,
    }
    ```

    | Key      | Type     | Description            |
    | -------- | -------- | ---------------------- |
    | `ret_code` | `int` | User ID                |


!!! failure "Bad Request"
    **Status Code**: `400 Bad Request`

    **Response Body**:

    ```json
    {
        "error": "<Error message>"
    }
    ```


[^_^]:
    end of a API end point



[^_^]:
    start of a API end point

## Update notification information

### `ANY` - /service/NotificationApiService/UpdateNotification

Use this request to update the notification information in redis from mongo database.



**Query Parameter(s)**:

| Parameter  | Type     | Description                             | Constraints           | Default | Required               |
| ---------- | -------- | --------------------------------------- | --------------------- | ------- | ---------------------- |
| `notification_id` | `string` | unique id for a notification               | N/A                   | N/A     | id is required        |

!!! note "Example"
    `service/NotificationApiService/UpdateNotification?notification_id=2`


**Request Body**: none


---

!!! success
    a return code is returned.

    **Status Code**: `200 OK`

    **Response Body**:

    ```json
    {
        "ret_code": <return code>,
    }
    ```

    | Key      | Type     | Description            |
    | -------- | -------- | ---------------------- |
    | `ret_code` | `int` | User ID                |


!!! failure "Bad Request"
    **Status Code**: `400 Bad Request`

    **Response Body**:

    ```json
    {
        "error": "<Error message>"
    }
    ```


[^_^]:
    end of a API end point



    [^_^]:
    start of a API end point

## Update permission information

### `ANY` - /service/NotificationApiService/UpdatePermission

Use this request to update the permission information in redis from mongo database.



**Query Parameter(s)**:

| Parameter  | Type     | Description                             | Constraints           | Default | Required               |
| ---------- | -------- | --------------------------------------- | --------------------- | ------- | ---------------------- |
| `permission_id` | `string` | unique id for a permisssion               | N/A                   | N/A     | id is required        |

!!! note "Example"
    `service/NotificationApiService/UpdatePermission?permission_id=2`


**Request Body**: none


---

!!! success
    a return code is returned.

    **Status Code**: `200 OK`

    **Response Body**:

    ```json
    {
        "ret_code": <return code>,
    }
    ```

    | Key      | Type     | Description            |
    | -------- | -------- | ---------------------- |
    | `ret_code` | `int` | User ID                |


!!! failure "Bad Request"
    **Status Code**: `400 Bad Request`

    **Response Body**:

    ```json
    {
        "error": "<Error message>"
    }
    ```


[^_^]:
    end of a API end point



    [^_^]:
    start of a API end point

## Update guild role information

### `ANY` - /service/NotificationApiService/UpdateGuildRole

Use this request to update the guild role information in redis from mongo database.


**Query Parameter(s)**:

| Parameter  | Type     | Description                             | Constraints           | Default | Required               |
| ---------- | -------- | --------------------------------------- | --------------------- | ------- | ---------------------- |
| `guild_id` | `string` | unique id for a guild               | N/A                   | N/A     | id is required        |

!!! note "Example"
    `service/NotificationApiService/UpdateGuildRole?guild_id=2`


**Request Body**: none


---

!!! success
    a return code is returned.

    **Status Code**: `200 OK`

    **Response Body**:

    ```json
    {
        "ret_code": <return code>,
    }
    ```

    | Key      | Type     | Description            |
    | -------- | -------- | ---------------------- |
    | `ret_code` | `int` | User ID                |


!!! failure "Bad Request"
    **Status Code**: `400 Bad Request`

    **Response Body**:

    ```json
    {
        "error": "<Error message>"
    }
    ```


[^_^]:
    end of a API end point



    [^_^]:
    start of a API end point

## Update role information

### `ANY` - /service/NotificationApiService/UpdateRole

Use this request to update the role information in redis from mongo database.


**Query Parameter(s)**:

| Parameter  | Type     | Description                             | Constraints           | Default | Required               |
| ---------- | -------- | --------------------------------------- | --------------------- | ------- | ---------------------- |
| `role_id` | `string` | unique id for a role               | N/A                   | N/A     | id is required        |

!!! note "Example"
    `service/NotificationApiService/UpdateRole?role_id=2`


**Request Body**: none


---

!!! success
    a return code is returned.

    **Status Code**: `200 OK`

    **Response Body**:

    ```json
    {
        "ret_code": <return code>,
    }
    ```

    | Key      | Type     | Description            |
    | -------- | -------- | ---------------------- |
    | `ret_code` | `int` | User ID                |


!!! failure "Bad Request"
    **Status Code**: `400 Bad Request`

    **Response Body**:

    ```json
    {
        "error": "<Error message>"
    }
    ```


[^_^]:
    end of a API end point



    [^_^]:
    start of a API end point

## Update user guild list information

### `ANY` - /service/NotificationApiService/UpdateUserGuildList

Use this request to update the user guild list information in redis from mongo database.

**Query Parameter(s)**:

| Parameter  | Type     | Description                             | Constraints           | Default | Required               |
| ---------- | -------- | --------------------------------------- | --------------------- | ------- | ---------------------- |
| `user_id` | `string` | unique id for a user               | N/A                   | N/A     | id is required        |

!!! note "Example"
    `service/NotificationApiService/UpdateUserGuildList?user_id=2`


**Request Body**: none


---

!!! success
    a return code is returned.

    **Status Code**: `200 OK`

    **Response Body**:

    ```json
    {
        "ret_code": <return code>,
    }
    ```

    | Key      | Type     | Description            |
    | -------- | -------- | ---------------------- |
    | `ret_code` | `int` | User ID                |


!!! failure "Bad Request"
    **Status Code**: `400 Bad Request`

    **Response Body**:

    ```json
    {
        "error": "<Error message>"
    }
    ```


[^_^]:
    end of a API end point



    [^_^]:
    start of a API end point

## Update user guild role information

### `ANY` - /service/NotificationApiService/UpdateUserGuildRole

Use this request to update the user guild role information in redis from mongo database.

**Query Parameter(s)**:

| Parameter  | Type     | Description                             | Constraints           | Default | Required               |
| ---------- | -------- | --------------------------------------- | --------------------- | ------- | ---------------------- |
| `user_id` | `string` | unique id for a user              | N/A                   | N/A     | id is required        |
| `guild_id` | `string` | unique id for a guild              | N/A                   | N/A     | id is required        |

!!! note "Example"
    `service/NotificationApiService/UpdateUserGuildRole?user_id=2&guild_id=2`


**Request Body**: none


---

!!! success
    a return code is returned.

    **Status Code**: `200 OK`

    **Response Body**:

    ```json
    {
        "ret_code": <return code>,
    }
    ```

    | Key      | Type     | Description            |
    | -------- | -------- | ---------------------- |
    | `ret_code` | `int` | User ID                |


!!! failure "Bad Request"
    **Status Code**: `400 Bad Request`

    **Response Body**:

    ```json
    {
        "error": "<Error message>"
    }
    ```


[^_^]:
    end of a API end point


 