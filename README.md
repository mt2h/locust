# Locust 

## Commands 

```bash
locust -f basic_http_host01.py -u 5 -r 1 -t 60s --headless
locust -f basic_http_host01.py -u 5 -r 1 -t 10s --headless --logfile mylog.log --loglevel DEBUG
locust -f on_start_stop.py -u 1 -r 1 --headless --only-summary
locust -f test_start_stop.py -u 2 -r 1 --headless --only-summary
locust -f basic_locust_taskdecorator_weight.py -u 1 -r 1 --headless --only-summary

locust -f basic_api.py -u 1 -r 1 --headless
```