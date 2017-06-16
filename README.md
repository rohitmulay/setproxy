# setproxy
<h2><b>How to set proxy on terminal in Linux operating systems.</b></h2>

Dowload the Python Script for proxy settings from this <a href="https://github.com/rohitmulay/setproxy">repository.</a>

Save it in the Home directory

In the terminal give the following command: 

<b> sudo python setproxy.py ProxyHost Port Username Password </b>

<b>EXAMPLE:</b> `sudo python setproxy.py 202.141.80.42 3128 rohitm2 password` 

Close the terminal and open it again and you are now connected to the internet on your terminal and good to go. 

If you don't have any username and password for your proxy network just give the following command: 

<b> sudo python setproxy.py ProxyHost Port </b>

<b>EXAMPLE:</b> `sudo python setproxy.py 202.141.80.42 3128` 

Close the terminal and open it again and you are now connected to the internet on your terminal and good to go. 
