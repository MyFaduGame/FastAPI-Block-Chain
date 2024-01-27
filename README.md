
# FastAPI BlockChain

This repository contains the Block Chain code consist with FastAPI and have an endpoints to validate the block chain. If you want you can add an sql or postgresql database in order to store the data into an either json format or in an column format.




## Installation

Install FastAPI Block Chain.

```bash
  git clone https://github.com/MyFaduGame/FastAPI-Block-Chain.git
  cd FastAPI-Block-Chain
  pip install -r requierements.txt
  uvicorn main:app --reload
```
    
## API Reference

#### Get all items

```http
  POST /mine_block/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `data` | `string` | **Required**. Data is Requiered |

#### Get item

```http
  GET /blockchain/
```

```http
  GET /validate/
```

```http
  GET /blockchain/last/
```



## Authors

- [@MyFaduGame](https://www.github.com/myfadugame)

