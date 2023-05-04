
![image](https://user-images.githubusercontent.com/77997252/236193277-fcbe1225-5796-47b1-a575-7f9c62a61639.png)

<h1>Load balancer</h1>
Ever wonder how Facebook, Linkedin, Twitter and other web giants are handling such huge amounts of traffic? They don’t have just one server, but tens of thousands of them. 
In order to achieve this, web traffic needs to be distributed to these servers, and that is the role of a load-balancer.


![image](https://user-images.githubusercontent.com/77997252/236193091-e732410f-a24b-46b6-835e-d72a0c8c96b5.png)


<h1>Tasks 📃</h1>
<ol> <li>0. Double the number of webservers</li>

<li>0-custom_http_response_header: Bash script that installs and configures Nginx on a server with a custom HTTP response header.
The name of the HTTP header is X-Served-By.
  The value of the HTTP header is the hostname of the server. </li>
  
  <h2>1. Install your load balancer</h2>

<li>1-install_load_balancer: Bash script that installs and configures HAproxy version 1.5 on a server.
Enables management via the init script.
  Requests are distributed using a round-robin algorithm. </li>
  
  <h2>2-puppet custom http response header</h2>

<li>2-puppet_custom_http_response_header.pp: Bash script that Just as in task #0, we’d like you to automate the task of creating a custom HTTP header response, but with Puppet.
The name of the custom HTTP header must be X-Served-By
  The value of the custom HTTP header must be the hostname of the server Nginx is running on</li>
  </ol>
