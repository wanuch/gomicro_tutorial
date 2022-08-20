# gomicro_tutorial
how to run front-end
=============================
go run ./cmd/web

how to setup broker-service
=============================
go get github.com/go-chi/chi/v5
go get github.com/go-chi/chi/v5/middleware
go get github.com/go-chi/cors

how to run broker-service
=============================
go run ./cmd/api

how to run docker 
=============================
go into project folder
docker-compose up -d

down the borker with Makefile
=============================
make down

stop the borker with Makefile
=============================
make stop

start the frontend with Makefile
=============================
make start

build the broker with Makefile
=============================
make up_build

