
<h1>Automating the process of setting up and hosting a website using Apache using Vagrant provisioning (IaaC)</h1>


<h2>Description</h2>
Project consists of a utilizing Vagrant provisioning and git bash to automate the setup of a website in a vm using Apache.


<br />


<h2>Languages and Utilities Used</h2>

- <b>Git Bash</b> 
- <b>Oracle VM Virtualbox 6.1 </b>
- <b>Vagrant boxes</b>
- <b>https://app.vagrantup.com/boxes/search</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Ubuntu 20 server

<h2>Program walk-through:</h2>

<p align="left">
- VM started using Vagrant init geerlingguy ubuntu2004 and editing the config using VIM to add the setup steps to the provisioning section <br/>

<img width="710" alt="vagrant provisoning" src="https://user-images.githubusercontent.com/85902399/204161378-41512417-0501-4e02-a239-b60e72378e6d.png">



<br />
<br />
We need to create one more file that is needed for the script.  this will be saved in the same directory as wordpress.conf  <br/>

<img width="367" alt="conf file" src="https://user-images.githubusercontent.com/85902399/204161546-4f5984c2-54f5-41a9-a8c0-35a7090e4cba.png">


<br />

load the VM using vagrant up command.  Once the script is completed, open a web browser to the local vm ip address http://192.168.39.21/.


<img width="1901" alt="automatedwordpress" src="https://user-images.githubusercontent.com/85902399/204161495-b2f3e108-4d50-46cc-ac37-dd82cc0dc119.png">




 
</p>
