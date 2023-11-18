### Сборка образа

```
docker image build . --tag=django:1.0
```

### Запуск контейнера

```
docker run -d -p 8000:8000 django:1.0
```

### Проверка

```
curl http://localhost:8000/api/v1/products/
```
