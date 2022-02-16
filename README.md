# raspi-kiosk

Hopefully a dockerised web browser to display a webpage as a kiosk

##Install
1- clone current project
````
git clone https://github.com/mwinterstorm/rspi-kiosk.git
````
2- edit docker-compose.yml
````
cd rspi-kiosk
nano docker-compose.yml
````
- replace [insertwebpage] with web page

4 - launch docker-compose
````
docker-compose up -d
````

#### Directory structure

The root directory generated for the app :
<pre>
├──  tools
├──  wifi-ap
├──  docker-compose.yml
├──  README.md
</pre>
