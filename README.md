# Build web apps with go

https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details
The chapter on Heroku deployment

## Requirements
* Heroku account
* Heroku toolbelt
* govendor - https://github.com/kardianos/govendor

Steps
* create repo
* create Procfile pointing to root folder
* create vendor `govendor init`
* grab vendor deps `govendor add +external`


Similar projects and guides:
https://github.com/heroku/go-getting-started
https://github.com/heroku/heroku-buildpack-go
