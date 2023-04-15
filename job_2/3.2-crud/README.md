# Сборка

docker build ./ --tag stock_product:0.0.1

# Запуск

docker run --name my_project -d -p 8000:8000 stock_product:0.0.1