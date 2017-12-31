# Chat
WSGI Server to chat with chatbot

### To implement:
1. Run the code using the chatbot_tf10 enviroment with: conda create -f chatbot_cpu_tf10.yml   
2. Add your saved model (the ckpt files) to the chatbot folder.  
3. In chatbot_load.py file change the ip_address to your local ip address (ex. '192.168.1.1').  
4. make sure port 5000 is open in linux using a code like sudo ufw allow 5000.  
5. Run chatbot_load.py file from terminal with python chatbot_load.py  
6. you can access your chatbot with the ip address noted above :5000 (ex. 192.168.1.1:5000) either on your local computer or a remote computer connected to your local network.  
