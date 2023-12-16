<h1 align="center">Dockerized cowrie honeypot with graphical kippo-graph analyzer</h1>

An all in one functional docker-compose project for the popular cowrie ssh honeypot project. In addition, a kippo-graph container will be deployed to graphically analyze the attacks.

![Kippo-graph demo animation](kippo-graph-animation.gif)

<h2>❗️ Please do not use if you do not know exactly how to secure the entire system. kippo-graph has not been maintained for a long time (12/2023).</h2>

# Installation

1. Clone the repo
   ```sh
   git clone https://github.com/luftl0ch/Dockerized-cowrie-honeypot-with-kippo-graph.git && cd Dockerized-cowrie-honeypot-with-kippo-graph
   ```
2. Execute docker-compose.
   ```sh
    docker-compose up 
   ```
3. Kippo-graph be available on http://127.0.0.1:8888.

You can change the Port of kippo-graph in the .env file. The database credentials are preconfigured in the following files: `.env` `configs/cowrie.cfg` `configs/graph-config.php`

# Based on:

<br/>

[cowrie](https://github.com/cowrie/cowrie) <br/>
[kippo-graph](https://github.com/ikoniaris/kippo-graph)
