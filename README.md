# nodejs
Processos de instalação do Nodejs e NodeEnv
Ao abrir o terminal de comandos digite:
sudo apt install python3-pip
Aguarde a instalação e digite em seguida:
pip3 install --user nodeenv
com isso teste a instalação do nodeenv digitando:
nodeenv --version
Abra um terminal novo, selecione a pasta onde ficará a pasta que irá
conter o NodeJs. Digite:
nodeenv nodejs-env
(nodeenv é o comando e nodejs-env é o nome da pasta que irá ser instalado o NodeJs)
Após a instalação, para assim ativar a versão do NodeJs, digite o comando :
source ./nodejs-env/bin/activate
E para testar(ter garantia que funcionou) digite:
node --version
Depois desses passos...
Tivemos o acesso ao codigo que o nosso professor passou no Github 
sendo ele: 
digite: sudo nano index.js

