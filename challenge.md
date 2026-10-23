# Challenge: Install It Yourself
1. sudo apt install -y htop, then htop. It shows CPU and memory usage of running processes.
2. apache2 version: <your version>. Command: apt show apache2 | head -4
3. Installed packages: <your number>. Command: apt list --installed | wc -l
4. sudo docker run --rm alpine echo "Hello from Alpine"
5. Docker key: /etc/apt/keyrings/docker.asc
   Docker sources file: /etc/apt/sources.list.d/docker.sources
6. sudo apt remove -y htop, then hash -r, then htop says command not found
