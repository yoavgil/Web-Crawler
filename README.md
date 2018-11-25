# perseus
## Graphical Web Crawler
----------------------------
### Requirements: python 3.6.6, pip, pipenv, node.js
### Running:
#### After cloning the repo:
Inside the 'crawler' directory, use <code>pipenv --python 3.6</code> to initialize a new pipenv. <br/>
Then use <code>pipenv sync</code> to install the required python packages <br/>
Inside the 'server' directory use <code>npm install</code> to install required node modules <br/>

#### Crawler
Use <code>pipenv run python3 core.py <logfile name> <start page url> <search depth> <search type (1=DFS, 2=BFS)> [keyword]</code> to run crawler.

