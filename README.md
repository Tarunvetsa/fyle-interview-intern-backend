# Fyle Backend Challenge

Clone the repository 
```
git clone https://github.com/Tarunvetsa/fyle-interview-intern-backend
```

### Install

```
docker-compose build
```

### Reset DB

```
docker-compose run web bash db_reset_initial.sh
```

### Start Server
Please be ensure to free the port to run the server

```
docker-compose up
```

### Run Tests

```
docker-compose run web pytest -vvv -s tests/
```

### Again Reset DB
To get correct coverage report, reset database
```
docker-compose run web bash db_reset.sh
```

### Get Coverage Report

```
docker-compose run web pytest --cov
```
