<h1>Port scanner with stealth scan</h1>

<p>This port scanner is a tool that use nmap to scan the ports. This tool facilitates port scanning and beautifies the output using batcat for this.</p>

<h2>Use</h2>
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

![Inicio del programa](https://github.com/user-attachments/assets/89644d16-c2f2-4d6f-942a-594421fb7534)

<p>Then the program will start scanning the ports and display them on the screen with batcat. It will show the versions of the services that are running on those ports.</p>

![Vídeo sin título (3)](https://github.com/user-attachments/assets/6971f187-5c26-4b0b-b5f9-aee561bc6ed0)

<h3>Important</h3>
<p>The program create two files (allPorts, target) that can be use to read again instead of execute de program again</p>
