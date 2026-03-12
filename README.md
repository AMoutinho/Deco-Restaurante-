# <p align=center><img align="center" src="https://i.postimg.cc/bNNN1n9T/icon4.png" /> </p>

<div id="inicio" align=center>
  <a href="#sobre">Sobre o Projeto</a>&nbsp;&nbsp;&nbsp;
  <a href="#requisitos">Requisitos para Instalação</a>&nbsp;&nbsp;&nbsp;  
  <a href="#instalacao">Instalação</a>&nbsp;&nbsp;&nbsp;  
  <a href="#autenticacao">Autenticação</a>&nbsp;&nbsp;&nbsp;  
  <a href="#funcionalidade">Funcionalidades</a>&nbsp;&nbsp;&nbsp;  
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;
  <a href="#telas">Telas</a>&nbsp;&nbsp;&nbsp;
  <a href="#desenvolvedor">Desenvolvedor</a>&nbsp;&nbsp;&nbsp; 
</div><br>

<h2 id="sobre">Sobre o projeto ℹ️</h2>
<p>O objetivo deste projeto é realizar a gestão de pequenos e médios restaurantes, de forma simples e direta, utilizando o framework Laravel.</p>

<h2 id="requisitos">Requisitos para Instalação 📝</h2>
<p>Para realizar a instalação é necessário você já possuir em sua máquina os seguintes componentes:</p>

➡️ PHP 8.0.1<br>
➡️ Composer<br><br>

<p>Além dos componentes citados, é recomendado que você também possua:</p>

➡️ NPM<br>

<h2 id="instalacao">Instalação ⚙️</h2>

<b>1)</b> Clone o repositório utilizando o comando:  
<i>git clone https://github.com/AMoutinho/Deco-Restaurante-</i><br>

<b>2)</b> Acesse o diretório através do comando:  
<i>cd restaurante</i><br>

<b>3)</b> Instale as dependências com o comando:  
<i>composer install</i><br>

<b>4)</b> Modifique o aquivo `.env` conforme seu ambiente<br>

<b>5)</b> Realize a migração do banco de dados com o comando:  
<i>php artisan migrate</i><br>

<b>6)</b> Inicie o servidor pelo comando:  
<i>php artisan serve --port=80</i><br>

<b>7)</b> Abra seu navegador e acesse através de:  
<i>http://localhost</i><br>

<h2 id="autenticacao">Autenticação 🛡️</h2>

<b>O projeto possui 2 níveis por padrão de usuários:</b><br>

<i>Administrador e Garçom</i><br><br>

<b>Após realizar todos os processos de instalação, segue as credenciais padrão de cada um desses usuários:</b><br>

<b>Versão Garçom</b><br>
<b>E-mail:</b> garcom@localhost<br>
<b>Senha:</b> 12345678<br><br>

<b>Versão Administrador</b><br>
<b>E-mail:</b> admin@localhost<br>
<b>Senha:</b> 12345678<br>

<h2 id="funcionalidade">Funcionalidades 🛠</h2>

<b>O projeto possui 2 níveis por padrão de usuários: <i>Administrador e Garçom</i>, abaixo seguem as funcionalidades em cada um dos perfis:</b><br><br>

<b>ADMINISTRADOR</b><br>
✅ <i>Adiciona um produto para comercialização</i><br>
✅ <i>Visualiza a quantidade de pessoas na mesa</i><br>
✅ <i>Visualiza os pedidos de cada mesa</i><br>
✅ <i>Visualiza as formas de pagamento utilizadas</i><br>
✅ <i>Visualiza um gráfico dos últimos 7 dias</i><br><br>

<b>GARÇOM</b><br>
✅ <i>Adiciona produtos às mesas</i><br>
✅ <i>Detalha os produtos de cada mesa</i><br>
✅ <i>Realiza o fechamento da conta</i><br>
✅ <i>Seleciona a forma de pagamento</i><br>
✅ <i>Resumo dos pedidos após pagamento</i><br>

<h2 id="tecnologias">Tecnologias</h2>

O sistema utiliza principalmente as seguintes tecnologias:

🔵 Framework Laravel<br>
🔵 Blade<br>
🔵 Javascript<br>

<h2 id="telas">Telas 🖥️</h2>

<div align="left">
  <img src="https://i.postimg.cc/yYpLWQRG/Pagina-Inicial.png" width="300">
  <img src="https://i.postimg.cc/zX2x3thx/Adc-Produtos-Mesas.png" width="300">
  <img src="https://i.postimg.cc/xTp6qxms/Fechar-Conta-Mesas.png" width="300">
  <img src="https://i.postimg.cc/8PXZsKvK/Forma-de-Pagamento-Conta-Mesa.png" width="300">
  <img src="https://i.postimg.cc/28903cW9/Mesas.png" width="300">
  <img src="https://i.postimg.cc/L6QxhCP7/Resumo-Mesa-Pagamento.png" width="300">  
</div>

<h2 id="desenvolvedor">Desenvolvedor 👨🏻‍💼</h2>

<a style="text-decoration:none;" href="https://github.com/AMoutinho" title="André Moutinho">
<img width="25" height="25" src="https://img.icons8.com/fluency/25/github.png" alt="github"/> André Moutinho
</a>