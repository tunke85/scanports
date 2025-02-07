<h1>Port scanner with stealth scan</h1>

<p>This port scanner is a tool that use nmap to scan the ports. This tool facilitates port scanning and beautifies the output using batcat for this.</p>

<ul>
  <li><h2>USE</h2></li>
</ul>
<h3>Installation: </h3>

<p>Firs of all, we clone the repository wherever we want</p>

   ```bash
   git clone https://github.com/tunke85/scanports
   ```
<p>Then we may put the script somewhere in the $PATH like /usr/bin or /usr/local/bin</p>

  ```bash
  cd scanports && cp scanports /usr/bin/.
  ```

<h3>How to use</h3>

<p>Call the script like a normal comand or execute the script in the directory</p>
  
  ```bash
  scanports
  ```
<p>or</p>

  ```bash
  cd scanports && ./scanports
  ```

<p>Now the program will ask you to enter the IP you want to scan. It is important to execute the script with sudo.</p>

https://github.com/user-attachments/assets/82951021-7e0f-4095-8cdf-8c7c5a5a02f5



<p>Then the program will start scanning the ports and display them on the screen with batcat. It will show the versions of the services that are running on those ports.</p>

![Vídeo sin título](https://github.com/user-attachments/assets/cf454162-70a8-41be-a63b-038a91c1cf36)
