
# Get Stock Data API

A simple API made to easily get option chain data for available stocks and also get real time updates of NIFTY, BANKNIFTY and GIFTNIFTY.
The API returns you Calls and Puts data for the stock including its OI, Change in OI, total volume and strike prices.


## API Reference

#### Get NIFTY and BANKNIFTY data

```http
  GET /api
```

#### Get option chain data for specific stocks

```http
  GET /ticker/${name}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `name`      | `string` | **Required**. Name of stock to search for. |


## Run Locally

- Clone the project

```bash
  git clone https://github.com/Mayank-Creater/Get-Stock-data-API.git
```

- Go to the project directory

```bash
  cd Get-Stock-Data-API
```

- Install dependencies

```bash
  pip install -r requirements.txt
```

- Start the server

```bash
  python api.py
```


## Deployment

To deploy this project run

```bash
  vercel deploy
```
in the directory containing the api.py file.

