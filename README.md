## Web-vulns-Environment
The docker-compose.yml file adds DVWA and BWapp instances on localhost for Web Pentesting
<hr>
Pulls and adds all necessary components to run DVWA and BWapp to localhost:
<p><br>
  <img src="bwapp.PNG" alt="bwapp" width="500"/></p>
  <p><br>
  <img src="dvwa.PNG" alt="dvwa" width="500"/></p>
    <p>
      - BWapp runs on localhost:10011</p>
    <p>
      - DVWA runs on localhost:10000</p>

Both these ports can be changed by changing the yml file.
<p>
<img src="ports.PNG" alt="ports" width="500"/></p>

Once repo is cloned, go path and run `docker-compose up`
<p> Note: Docker must be installed</p>
