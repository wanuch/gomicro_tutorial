# gomicro_tutorial
how to run front-end
=============================
go run ./cmd/web

how to setup broker-service
=============================
go get github.com/go-chi/chi/v5
go get github.com/go-chi/chi/v5/middleware
go get github.com/go-chi/cors

how to setup logger service
=============================
go get go.mongodb.org/mongo-driver/mongo
go get go.mongodb.org/mongo-driver/mongo/options

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

build the broker, auth, logger services with Makefile
=============================
make up_build

setup postgress db
=============================
go get github.com/jackc/pgconn
go get github.com/jackc/pgx/v4
go get github.com/jackc/pgx/stdlib

mongodb setup
=============================
in the mongo compass, enter below:
mongodb://admin:password@localhost:27017/logs?authSource=admin&readPreference=primary&appname=MongDB%20Compass&directConnection=true&ssl=false
