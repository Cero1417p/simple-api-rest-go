# Link
Tutorial https://go.dev/doc/tutorial/web-service-gin

# to init
go run .

# to make request
$ curl http://localhost:8080/albums \
--header "Content-Type: application/json" \
--request "GET"

$ curl http://localhost:8080/albums 
--include \
--header "Content-Type: application/json" \
--request "POST" \
--data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'