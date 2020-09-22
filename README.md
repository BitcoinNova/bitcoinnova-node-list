# BitcoinNova Nodes List (API)
A API JSON that shows you bitcoin nova nodes and their availability. Currently it is used in the mobile wallet.

## Install Requirements
 
 - Python 3.8
 - MySql Server
 - Redis Server

`sudo apt-get install python3.8`
`pip install -r requirements.txt`
`sudo apt-get install mysql-server`
`sudo apt-get install redis-server`

## Adjusting Settings

```ini
DBHOST = os.getenv('NODEBTN_MYSQL_HOST', 'localhost')
DBUSER = os.getenv('NODEBTN_MYSQL_USER', 'user')
DBNAME = os.getenv('NODEBTN_MYSQL_NAME', 'dbname')
DBPASS = os.getenv('NODEBTN_MYSQL_PASS', 'dbpassword')

```

## Running
 `python bitcoinnova_node_live.py`