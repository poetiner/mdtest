# mdtest
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

|---------------------| Request-response| CPU bound(fibonacci(25)) | 
| --------------------|-----------------|--------------------------|
| Pure socket server  | 14600 per-sec   | 4.79432225227356 sec     |
| Select              | 2000  per-sec   | 0.7350335121154785 sec   |
| Selectors           | 13000 per-sec   | 0.7619962692260742 sec   |
| HTTP-servers        | 75    per-sec   | 0.5440094470977783 sec   |
