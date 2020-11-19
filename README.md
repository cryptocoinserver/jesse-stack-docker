# Jesse quick start

Quick start for jesse, all you need is install [docker  compose](https://docs.docker.com/compose), clone this repo.


## 1. Start Jesse container:
```sh
docker-compose run jesse bash
```

## 2. Connect to the CLI of the Jesse container


## 3. Upgrade Jesse pkg to the latest version:
```sh
pip install -U jesse
```

## 4. Jesse container - Create your project:
```sh
jesse make-project name-of-project
```

## 5. Jesse container - Navigate to the project root directory:
```sh
cd /home/name-of-project
```

## 6. Jesse container - Import the candle history:
```sh
jesse import-candles Binance BTCUSDT 2019-01-01
```

## You're good to go! Run a backtest:
```sh
jesse backtest 2019-06-01 2020-01-01 --chart
```

Web interface for backtesting result chart: `http://localhost:3000`
