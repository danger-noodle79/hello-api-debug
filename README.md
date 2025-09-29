# Hello API!

A tiny lab where Danger Noodle learns to read the runes of APIs.

## Why this exists
I’m moving into AI. APIs are the doors my models walk through. This repo is my first stone in the cathedral.

## Mini “API Debug” checklist
- [ ] Know HTTP verbs (GET, POST, PUT, DELETE)
- [ ] Know status codes (200/400/401/403/404/500)
- [ ] Read JSON without crying
- [ ] Make a test request (e.g., https://httpbin.org/get)



## HTTP Status Cheat Sheet (for future me)

| Code | Meaning              | First things to check                           |
|-----:|----------------------|--------------------------------------------------|
| 200  | OK                   | Party on.                                       |
| 400  | Bad Request          | URL/params/JSON shape; missing required fields. |
| 401  | Unauthorized         | Authorization header/token present & valid?     |
| 403  | Forbidden            | Token valid but lacks permission/scope.         |
| 404  | Not Found            | Endpoint path/ID correct? Environment correct?  |
| 500  | Internal Server Err. | Try again; capture request-id; check logs.      |
