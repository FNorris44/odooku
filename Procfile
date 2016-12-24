web: odooku --database-maxconn 8 --redis-maxconn 8 wsgi $PORT
worker: odooku --database-maxconn 2 --redis-maxconn 2 cron --max-cron-threads 2
