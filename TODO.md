Goal: To explore deeply on deployment and logging setups for django web apps. Work in conjunction with research done for blog post
List of action items:
phase 1:
1. Simple Django web backend. JWT for auth
2. Logging setup to log into std out with something vector for log collection service
3. Typical deployment setup of nginx + gunicorn + django in VM or managed service
4. Dockerized setup for deployment to cloud run or some other container service
5. Load testing

phase 2: 
1. Websocket server setup and deployment with redis pub/sub
2. bg workers setup and deployment with redis message queue
3. Explore deeply on fan out concepts
4. Connection pooling
5. caching

Optional stuff to try:
1. Async django