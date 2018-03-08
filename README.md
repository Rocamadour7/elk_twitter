# ELK Twitter

Twitter fetcher and monitoring using the ELK stack (Elasticsearch, Logstash, Kibana).

![Kibana Dashboard](images/dashboard.png)

### Requirements
* Docker
* Docker-compose

### Usage
1. Clone this repo `git clone https://github.com/Rocamadour7/elk_twitter.git`
2. Navigate into the directory `cd elk_twitter/`
3. Create an app on [Twitter Apps](https://apps.twitter.com/app/new) *(For website you can use http://127.0.0.1/)*
4. Create a .env file based on the [.env.example](.env.example) and copy your twitter app keys.
5. On a terminal run `docker-compose up` *(Or `docker-compose up -d` for detach mode)*
6. Navigate into [Kibana](http://localhost:5601) *(http://localhost:5601)*