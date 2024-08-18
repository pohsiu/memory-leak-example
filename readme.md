
### Run the web server in inspect mode
```yarn dev```

### Open Browser in `chrome://inspect`
1. Take snapshot before HTTP req simulation
2. Run k6 https simulations
3. Take another snapshot for diagnosis


### Simulate HTTP request with 100 virtual users and 2mins duration
```k6 run --duration 2m --vus 100 request.js```
