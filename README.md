# golangdocker
1.Create golang languages
     run command go mod init puza.com/updev เราก็จะได้ go.mod ซึ่งจะทำการเก็บไว้ใน Root directory
     Packages คือ Source Code ของภาษา Go ที่อยู่ใน Directory
Module คือ Collection ของ Package ที่มีการทำงานด้วยวัตถุประสงค์เดียวกัน
   - go run main.go
## ---------------------------------------------------------------------------- ##

2.Build images docker 
    - docker build --tag golangdocker .
    - docker images
    - docker run -p 8080:8080 golangdocker
    - docker run -d -p 8080:8080 golangdocker
    - docker ps
    - docker exec -it ID bash
