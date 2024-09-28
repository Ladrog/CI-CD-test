# Kоманды для запуска контейнера c backend-сервером

1. docker image build -t "my_backend_image" ./stocks_products
2. docker run -d -p "example":5050 --env-file ./stocks_products/stocks_products/.env --name "my_backend_container" "my_backend_image"