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
Tivemos o acesso ao código que o nosso professor passou no Github 
sendo ele:
var http = require('http');
http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Helloworld');
}).listen(5000);
(copie o codigo porque mais tarde será usado)

Digite no terminal de comandos agora no Visualcode:  
sudo nano index.js 
logo depois digite: 
node index.js
Depois: 
sudo nano index.js 
Com este comando abrirá um novo terminal onde vc adciona o codigo lá do começo disponibilizado pelo professor, e modifique colocando seu nome completo e a data. (Mudamos o numero da porta tambem).
Para testar coloque no firefox: localhost:(numero da sua porta).
