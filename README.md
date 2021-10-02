# clunker
Test service with a reliability level that can be set at runtime

Clunker is a crappy old an unreliable service that can be made to throw errors at runtime. 

TODO
- implement GET /hello
- implement PUT /errorlevel/$LEVEL, where LEVEL is a number between 0 and 100, where 0 is means all request complete OK and 100 means all requests fail with HTTP 500
