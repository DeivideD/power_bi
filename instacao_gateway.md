## Gateway – Instalação

### Instalando o Gateway 
1. Acesse o endereço http://powerbi.com, clique em Entrar e informe o seu usuário e senha: 
<br /><br />
![Alt text](./img/Gateway-1.png?raw=true "Work Space")
<br /><br />
2. Feito o acesso em sua conta, clique no ícone de download na parte superior e selecione a opção Gateway de Dados.<br /><br />

![Alt text](./img/Gateway-2.png?raw=true "Work Space")
##### Ao clicar em Gateway de Dados, você será redirecionado para a página de download do Gateway.
<br /><br />
3. Clique em Download Gateway para iniciar o download do arquivo de instalação:
<br /><br />
![Alt text](./img/Gateway-3.png?raw=true "Work Space")

4. Ao finalizar o download, execute o arquivo baixado.
##### Ele abrirá um wizard para instalação do Gateway.<br /><br />

5. Clique em Próximo, como mostra a imagem abaixo:
<br /><br />

![Alt text](./img/Gateway-4.png?raw=true "Work Space")
<br /><br />

6. Selecione o Gateway do tipo On-Premises Data Gateway e clique em Próximo:<br /><br />

![Alt text](./img/Gateway-5.png?raw=true "Work Space")
###### Após escolher o tipo de Gateway e ter clicado em próximo, ele fará uma rápida análise. Aguarde até que ela termine:<br /><br />
![Alt text](./img/Gateway-6.png?raw=true "Work Space")
<br /><br />

7. Ao finalizar a análise, clique em Avançar.
<br /><br />
![Alt text](./img/Gateway-7.png?raw=true "Work Space")
<br /><br />

8. Na etapa seguinte, aceite os termos de uso e a política de privacidade e clique em Instalar:<br /><br />
![Alt text](./img/Gateway-8.png?raw=true "Work Space")
<br /><br />
###### Aguarde o término da instalação:
![Alt text](./img/Gateway-9.png?raw=true "Work Space")
<br /><br />

9. Ao concluir a instalação, será necessário que digite o e-mail da sua conta do Power BI para utilização e a configuração do Gateway, por fim, clique em Entra:<br /><br />
![Alt text](./img/Gateway-10.png?raw=true "Work Space")
###### Se desejar, nomeie o Gateway criado.

10. Escolha uma senha de no mínimo 8 caracteres, caso seja necessário reinstalar o Gateway.
<br /><br />

11. Clique em Configurar:
<br /><br />
![Alt text](./img/Gateway-11.png?raw=true "Work Space")
#### O Gateway foi instalado e já está online. 
#### O próximo passo será configurá-lo no Power BI Web.
<br /><br />
![Alt text](./img/Gateway-12.png?raw=true "Work Space")

<br /><br /><br /><br />
### Configurando o Gateway
<br /><br />
1. Abra o Power BI Web.

2. Clique no ícone de Configurações e selecione a opção Gerenciar Gateways, como mostra a imagem abaixo:<br /><br />

![Alt text](./img/Gateway-13.png?raw=true "Work Space")
#### Observe que o Gateway criado já foi reconhecido:
<br /><br />
![Alt text](./img/Gateway-14.png?raw=true "Work Space")

#### Agora precisamos adicionar fontes de dados para utilizar o Gateway criado.
#### As Fontes de Dados são responsáveis por armazenar as credenciais (servidor, base de dados, usuário, senha e modo de autenticação) para que os relatórios e dashboards possam conectar com os dados locais.
#### Vale ressaltar, que um Gateway pode ter uma ou mais Fontes de Dados associadas.
<br /><br />

3. Clique em Adicionar Fontes de Dados para usar o Gateway:
<br /><br />
![Alt text](./img/Gateway-15.png?raw=true "Work Space")
<br /><br />
4. Escolha um nome e um tipo para sua Fonte de Dados.
<br /><br />
5. Digite o nome do servidor onde está localizado seu banco de dados ou qualquer que seja sua fonte de dados.
<br /><br />
6. Digite o nome da Base de Dados.
<br /><br />
7. Escolha o método de autenticação.
<br /><br />
![Alt text](./img/Gateway-16.png?raw=true "Work Space")
<br /><br />
#### Ao escolher o método de autenticação, abrirá mais campos, para colher as credenciais para autenticação.
<br /><br />
8. Digite o nome de usuário e senha, após, clique em Adicionar.
<br /><br />
![Alt text](./img/Gateway-17.png?raw=true "Work Space")
#### Com os dados digitados corretamente, após clicar em adicionar, apresentará uma mensagem de Conexão bem-sucedida:
<br /><br />
![Alt text](./img/Gateway-18.png?raw=true "Work Space")

### Gerenciando as permissões do Gateway

#### Após realizar a conexão, é necessário conceder acesso aos usuários autorizados a utilizar a Fonte de Dados do Gateway. Apenas os usuários associados a fonte de dados poderão publicar relatórios com a Fonte de Dados em questão.
<br /><br />
1. Para isto, clique na aba Usuário.
<br /><br />
#### Por padrão, o usuário criador do Gateway, estará listado para 
receber a permissão de acesso a Fonte de Dados criada.
<br /><br />
2. Caso deseje adicionar outros usuários, basta digitar o e-mail do mesmo e clicar em adicionar:
<br /><br />
![Alt text](./img/Gateway-19.png?raw=true "Work Space")
#### Agora iremos vincular o Gateway criado a um conjunto de dados existente (de um dashboard previamente publicado)
<br /><br />
3. Após realizar a inclusão dos usuários, clique no ícone de Configurações e selecione a opção Configurações:
![Alt text](./img/Gateway-20.png?raw=true "Work Space")
<br /><br />
4. Selecione a aba Conjunto de Dados (Nesta aba serão listados todos conjuntos de dados existentes).
<br /><br />
5. Selecione o Conjunto de Dados que deseja vincular ao Gateway.
<br /><br />
6. Na opção Usar um Gateway de Dados, troque para Ativado.
<br /><br />
7. Selecione o Gateway criado.
<br /><br />
8. Clique em Aplicar:
<br /><br />
![Alt text](./img/Gateway-21.png?raw=true "Work Space")
<br /><br />
#### Pronto, agora o Dashboard que antes buscava os dados a partir da Fonte de Dados Teste_Bi9, agora irá utilizar o Gateway criado.

#### Com o gateway criado, é possível agendar atualizações para o mesmo.

#### No campo Atualizar Frequência da opção Atualização Agendada podemos programar diversas atualizações, que podem ser diariamente ou semanalmente.

#### A opção Diariamente permite escolher vários horários para a atualização, sendo que esses horários devem ter o intervalo mínimo de 30 minutos entre eles.

#### Já na opção Semanalmente, conseguimos escolher os dias que ocorrerão as atualizações e os horários em cada um dos dias escolhidos.

Para criar uma atualização agendada, basta seguir os seguintes passos:
<br /><br />
9. Clique na opção Atualização Agendada:
<br /><br />
![Alt text](./img/Gateway-22.png?raw=true "Work Space")
<br /><br />
10. Ative a opção Manter Seus Dados Atualizados.
<br /><br />
11. Selecione a Frequência de Atualização dos dados (Diariamente ou Semanalmente).
<br /><br />
12. Escolha o Fuso Horário desejado.
<br /><br /> 
13. Adicione horas para que os dados sejam atualizados.
<br /><br />
14. Clique em aplicar:
![Alt text](./img/Gateway-23.png?raw=true "Work Space")

#### Seu gateway será atualizado conforme o agendamento realizado.
