
### Run the web server in inspect mode
```yarn dev```

### Open Browser in `chrome://inspect`
1. Take snapshot before HTTP req simulation
2. Run k6 https simulations
3. Take another snapshot for diagnosis


### Simulate HTTP request with 100 virtual users and 2mins duration
```k6 run --duration 2m --vus 100 request.js```
https://grafana.com/docs/k6/latest/using-k6/http-requests/


### Reference Docs
https://vocus.cc/article/61176c17fd89780001942f1c
https://blog.logrocket.com/understanding-memory-leaks-node-js-apps/?source=post_page-----1ec79b3b223f--------------------------------
https://medium.com/john-lewis-software-engineering/we-had-a-leak-identifying-and-fixing-memory-leaks-in-next-js-622977876697