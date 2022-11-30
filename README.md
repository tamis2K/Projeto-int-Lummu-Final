<h1 align="center"> Projeto Integrador MVP - Lummu </h1>


<p align="center">
<img src="imagens/FuncionamentoProjeto.gif">
</p>

<h1 align="center"> :bulb: Estrutura do Projeto :bulb: </h1>

<p align="center">
<img src="imagens/EstruturaProjeto.png" width="900" height="490">
</p>


> - Foi Adaptado um interruptor interno; 
> - Adicionado um NODEMCU com relé para ativação e desativação da corrente elétrica da lâmpada onde assim faz com que ligue e desligue;
> - Todos os componentes ( Relé, Node MCU e bateria) estão armazenados numa case ligado a corrente elétrica;
> - Utilizado um Relé de 3V onde fica armazendo no case.

<p align="center">
<img src="imagens/ComponentesInternos.png">
</p>
<p align="center">
<img src="imagens/Lampada.png">
</p>

<h1 align="center"> :computer: Programação :computer: </h1>

<p align="center">
<img src="imagens/7.png" width="500" height="150">
</p>

<img src="https://cdn1.iconfinder.com/data/icons/mix-color-4/502/Untitled-21-512.png" width="20" height="20"> [Sinric Pro](https://portal.sinric.pro/register), acesse e crie sua conta, crie um novo dispositivo, pegue as credências e defina as seguintes variáveis.


```js
#define APP_KEY           "c9a60600-af2c-4a5e-8936-cc619e93d12a" 
#define APP_SECRET        "e6979de6-9e34-43e5-8759-2df0ec17f5c2-da731060-ad89-4851-9303-1322fe232cfa"
#define SWITCH_ID         "6349f0a416440f13ff7d2836"
```
Configure sua rede Wi-Fi

```js
#define WIFI_SSID         "Redminote8"  - NOME DA REDE  
#define WIFI_PASS         "12345678" - SENHA DA REDE
```

Baixa o app da Alexa e adicione o dispositivo.

<img src="imagens/TutorialConfigAlexa.pdf" width="450" height="250">

# Contribua 

1 - Fork it

2 - Cria sua feature branch (git checkout -b my-new-feature)

3 - Commit suas mudanças (git commit -am "Added some feature")

4 - Push na sua branch (git push origin my-new-feature)

5 - Crie novo Pull Request