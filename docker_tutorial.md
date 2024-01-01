1. clone a repository
`docker cp repo:/git/getting-started/ .`

2. Build
`cd getting-started`
`docker build -t docker101tutorial .`

3. Run
`docker run -d -p 80:80 \ --name docker-tutorial docker101tutorial`


4. Share
`docker tag docker101tutorial [userName]/docker101tutorial`
`docker push [userName]/docker101tutorial`


