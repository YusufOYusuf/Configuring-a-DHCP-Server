<h1>Configuring a DHCP Server</h1>


<h2>Description</h2>
In this lab, I configured a DHCP Server. A DHCP, an acronym for Dynamic Host Configuration Protocol, server depends on the network operating system that is being used. In DHCP Server, a scope is configured to determine the address pool of IPs  that the server can provide to DHCP client. 
<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 

<h2>Program walk-through:</h2>

<p align="center">
Start by clicking the Server Manager: <br/>
<img src="https://i.postimg.cc/Bn4yKQpN/Screen-Shot-2022-06-17-at-6-29-29-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
<br />
Click the flag icon and from there click the Complete DHCP configuration link:  <br/>
<img src="https://i.postimg.cc/m2fgyqLL/Screen-Shot-2022-06-17-at-6-32-27-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
Click Commit then Close: <br/>
<img src="https://i.postimg.cc/TPf6yMJS/Screen-Shot-2022-06-17-at-6-34-45-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
  <img src="https://i.postimg.cc/Njy415p2/Screen-Shot-2022-06-17-at-6-35-42-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
Click the flag icon to make sure the configuration completed for DHCP Server at 366m-V2:  <br/>
<img src="https://i.postimg.cc/GhstQwTt/Screen-Shot-2022-06-17-at-6-39-08-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
Click the search button and type Services and press enter:  <br/>
<img src="https://i.postimg.cc/8cGFJZww/Screen-Shot-2022-06-17-at-6-42-03-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
In the Right pane, scroll down and double click DHCP Server:  <br/>
<img src="https://i.postimg.cc/SsSPVhZM/Screen-Shot-2022-06-17-at-6-46-05-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
   
  
<br />
In the DHCP Server Properties (Local Computer) window, click the Stop button and wait for the process to complete:  <br/>
<img src="https://i.postimg.cc/ZKmhvGm6/Screen-Shot-2022-06-17-at-6-48-46-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
  
  
  <br />
Click the Start button and wait for the process to complete:  <br/>
<img src="https://i.postimg.cc/ZY7QFn1P/Screen-Shot-2022-06-17-at-6-51-54-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
 <br />
Finish task by clicking ok:  <br/>
<img src="https://i.postimg.cc/ZY7QFn1P/Screen-Shot-2022-06-17-at-6-51-54-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br /> 
  
  
  
  
 <br />
Close the Service window and go to Windows Administrative Tools:  <br/>
<img src="https://i.postimg.cc/7YYrNjs7/Screen-Shot-2022-06-17-at-6-55-31-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
  <br />
In the right pane double click DHCP:  <br/>
<img src="https://i.postimg.cc/kXQ4zrq5/Screen-Shot-2022-06-17-at-6-57-05-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
  <br />
IN the right pane, navigate to DHCP then 366m-v2.mshome.net then IPv4:  <br/>
<img src="https://i.postimg.cc/nc1sMsMx/Screen-Shot-2022-06-17-at-6-59-35-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<img src="https://i.postimg.cc/P5z0gj62/Screen-Shot-2022-06-17-at-7-00-25-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
  <br />
Right click IPv4 and select New Scope:  <br/>
<img src="https://i.postimg.cc/Y0yk5wbv/Screen-Shot-2022-06-17-at-7-03-47-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
 <br />
In the New Scope Wizard window, click the Next button:  <br/>
<img src="https://i.postimg.cc/yNkVTxPw/Screen-Shot-2022-06-17-at-7-05-07-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
  <br />
Type Name and Description and then click next:  <br/>
<img src="https://i.postimg.cc/mrCFSm8x/Screen-Shot-2022-06-17-at-7-07-30-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
 <br />
In the IP range window, type Start IP address as 192.168.137.2 then type End IP address as 192.168.137.250, and then click next button:  <br/>
<img src="https://i.postimg.cc/D07Scsz7/Screen-Shot-2022-06-17-at-7-13-26-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  <br />
In the Add Exclusions And Delay window, click Next without adding any excluded addresses or delays:  <br/>
<img src="https://i.postimg.cc/wjRDMXyr/Screen-Shot-2022-06-17-at-7-15-10-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
   <br />
In the Least Duration window, in the Days text box type 3 and click the Next button:  <br/>
<img src="https://i.postimg.cc/cJBqq8mK/Screen-Shot-2022-06-17-at-7-17-23-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
   <br />
In the Configure DHCP Options window, click the Next button to proceed to the next step:  <br/>
<img src="https://i.postimg.cc/PqSCXNfx/Screen-Shot-2022-06-17-at-7-19-51-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
   <br />
In the Router (Default Gateway) window, type IP address as 192.168.137.1 and then click the add button:  <br/>
<img src="https://i.postimg.cc/L8VHMX2b/Screen-Shot-2022-06-17-at-7-24-38-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
   <br />
Once the address is added, click the Next button three times:  <br/>
<img src="https://i.postimg.cc/VsDfT5sZ/Screen-Shot-2022-06-17-at-7-26-54-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
  <img src="https://i.postimg.cc/4yNBSW4d/Screen-Shot-2022-06-17-at-7-29-49-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
  <img src="https://i.postimg.cc/FRfyqzwM/Screen-Shot-2022-06-17-at-7-30-55-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
    
   <br />
In the Activate Scope window, verify that the Yes, I want to activate this scope now radio button is selected by default and click the Next button:  <br/>
<img src="https://i.postimg.cc/Hs1Nw1yY/Screen-Shot-2022-06-17-at-7-31-48-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
    
   <br />
Click the Finish button to create the scope:  <br/>
<img src="https://i.postimg.cc/cJ6WpGTq/Screen-Shot-2022-06-17-at-7-34-27-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
