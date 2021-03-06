# Backlog
O Backlog é uma lista de funcionalidades desejadas de um produto, ou seja, os requisitos que um cliente espera receber ao final do projeto, descrito com sua própria linguagem. Ele cresce e muda à medida que se aprende mais sobre o produto e seus usuários. Para estruturar o Product Backlog nós utilizamos as chamadas histórias de usuário, elas contém a descrição detalhada dos requisitos de cada solicitação a ser implementada.

## Backlog e histórias de usuário
<style type="text/css">
.tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-vxga{background-color:#ffffff;text-align:center;vertical-align:middle}
.tg .tg-d7mt{background-color:#cbcefb;border-color:#cbcefb;text-align:center;vertical-align:middle}
.tg .tg-f189{background-color:#dae8fc;text-align:center;vertical-align:middle}
.tg .tg-p7cy{background-color:#ffffff;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-y0n7{background-color:#efefef;text-align:center;vertical-align:middle}
.tg .tg-xnem{background-color:#ffffff;border-color:#cbcefb;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-d7mt"><span style="font-weight:bold">Épico</span></th>
    <th class="tg-d7mt"><span style="font-weight:bold">Feature</span></th>
    <th class="tg-d7mt"><span style="font-weight:bold">ID</span></th>
    <th class="tg-d7mt"><span style="font-weight:bold">US</span></th>
    <th class="tg-d7mt"><span style="font-weight:bold">Critérios de Aceite</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-f189" rowspan="17">E01 - Usuário beneficiário</td>
    <td class="tg-p7cy" rowspan="3">FE01 - Cadastro e autenticação</td>
    <td class="tg-y0n7">US01</td>
    <td class="tg-y0n7">Eu, como usuário beneficiário, gostaria de me cadastrar no Doarti, para poder receber doações.</td>
    <td class="tg-y0n7">Beneficiário deve enviar e-mail para a equipe do Doarti para se cadastrar.</td>
  </tr>
  <tr>
    <td class="tg-vxga">US02</td>
    <td class="tg-vxga"><span style="color:#000">Eu, como usuário beneficiário, gostaria de realizar meu login, para poder ver as informações da minha instituição</span></td>
    <td class="tg-vxga"><span style="color:#000">Beneficiário deve fornecer e-mail e senha válidos.</span></td>
  </tr>
  <tr>
    <td class="tg-y0n7">US03</td>
    <td class="tg-y0n7"><span style="color:#000">Eu, como usuário beneficiário, gostaria de realizar meu logout, para ter liberdade de ver minha conta em outros dispositivos</span></td>
    <td class="tg-y0n7"><span style="color:#000">Ter um botão para o usuário poder se desconectar do aplicativo.</span></td>
  </tr>
  <tr>
    <td class="tg-vxga" rowspan="3">FE02 - Dados cadastrais</td>
    <td class="tg-vxga">US04</td>
    <td class="tg-vxga"><span style="color:#000">Eu, como usuário beneficiário, gostaria de visualizar meus dados cadastrais, para poder verificá-los e validá-los</span></td>
    <td class="tg-vxga"><span style="color:#000">Ter uma tela com as informações do usuário.<br />Pegar dados do usuário do banco de dados.</span></td>
  </tr>
  <tr>
    <td class="tg-y0n7">US05</td>
    <td class="tg-y0n7">Eu, como usuário beneficiário, gostaria de editar meus dados cadastrais, para poder corrigir erros/mudanças de cadastro</td>
    <td class="tg-y0n7">Botão na tela de perfil para editar dados. <br /> Tela com dados cadastrais. <br /> Caixa de edição nos dados para editá-los. <br /> Botão para salvar os novos dados.</td>
  </tr>
  <tr>
    <td class="tg-vxga">US06</td>
    <td class="tg-vxga">Eu, como usuário beneficiário, gostaria de alterar minha senha para manter minha conta segura</td>
    <td class="tg-vxga">Ter botão de edição de senha na tela de perfil. <br /> Enviar e-mail com instruções de alteração de senha.</td>
  </tr>
  <tr>
    <td class="tg-xnem" rowspan="4">FE03 - Gerenciar campanhas</td>
    <td class="tg-y0n7">US07</td>
    <td class="tg-y0n7">Eu, como usuário beneficiário, gostaria de criar campanhas, para poder receber doações</td>
    <td class="tg-y0n7">Ter botão para criar campanha. <br /> Ter campos para dados da campanha. <br /> Ter botão para salvar campanha.</td>
  </tr>
  <tr>
    <td class="tg-vxga">US08</td>
    <td class="tg-vxga">Eu, como usuário beneficiário, gostaria de editar campanhas, para que elas estejam de acordo com a companhia</td>
    <td class="tg-vxga">Ter botão para editar campanha. <br /> Levar usuário para tela de criação.</td>
  </tr>
  <tr>
    <td class="tg-y0n7">US09</td>
    <td class="tg-y0n7">Eu, como usuário beneficiário, gostaria de excluir campanhas, para ter maior controle delas.</td>
    <td class="tg-y0n7">Ter botão para excluir campanhas. <br /> Mensagem de confirmação para evitar erros.</td>
  </tr>
  <tr>
    <td class="tg-vxga">US10</td>
    <td class="tg-vxga">Eu, como usuário beneficiário, gostaria de visualizar minhas campanhas criadas, para ter detalhes das minhas campanhas.</td>
    <td class="tg-vxga">Ter botão de ver campanhas. <br /> Ter uma lista com as minhas campanhas. <br /> Pegar dados do banco de dados.</td>
  </tr>
  <tr>
    <td class="tg-vxga" rowspan="2">FE04 - Gerenciar doações</td>
    <td class="tg-y0n7">US11</td>
    <td class="tg-y0n7">Eu, como usuário beneficiário, gostaria de visualizar as doações recebidas, para ter histórico das minhas doações</td>
    <td class="tg-y0n7">Ter dados das doações na tela da campanha.</td>
  </tr>
  <tr>
    <td class="tg-vxga">US12</td>
    <td class="tg-vxga">Eu, como usuário beneficiário, gostaria de filtrar as doações recebidas, para poder pesquisar por doações especificas</td>
    <td class="tg-vxga">Ter uma entrada de filtros na lista de doações.</td>
  </tr>
  <tr>
    <td class="tg-vxga" rowspan="3">FE05 - Interagir com usuário doador</td>
    <td class="tg-y0n7">US13</td>
    <td class="tg-y0n7">Eu, como usuário beneficiário, gostaria de visualizar informações sobre os doadores que doaram para minha campanha, para poder entrar em contato com eles caso necessário</td>
    <td class="tg-y0n7">Mostrar dados do doador na lista de doações</td>
  </tr>
  <tr>
    <td class="tg-vxga">US14</td>
    <td class="tg-vxga">Eu, como usuário beneficiário, gostaria de entrar em contato com o usuário doador que doou para minha campanha, para poder acertar buscas por doações</td>
    <td class="tg-vxga">Ter botão para enviar mensagem ao doador na lista de doadores.</td>
  </tr>
  <tr>
    <td class="tg-y0n7">US15</td>
    <td class="tg-y0n7">Eu, como usuário beneficiário, gostaria de visualizar as mensagens recebidas de doadores, para poder respondê-los</td>
    <td class="tg-y0n7">Ter uma aba de mensagens.</td>
  </tr>
  <tr>
    <td class="tg-vxga" rowspan="2">FE06 - Visualizar seção de dúvidas</td>
    <td class="tg-vxga">US16</td>
    <td class="tg-vxga"><span style="color:#000">Eu, como usuário beneficiário, gostaria de visualizar informações sobre o Doarti, para poder saber mais sobre o aplicativo</span></td>
    <td class="tg-vxga"><span style="color:#000">Ter uma aba com informações sobre o Doarti</span></td>
  </tr>
  <tr>
    <td class="tg-y0n7">US17</td>
    <td class="tg-y0n7">Eu, como usuário beneficiário, gostaria de entrar em contato com a equipe do Doarti, para tirar dúvidas ou resolver problemas</td>
    <td class="tg-y0n7">Ter e-mail do Doarti na tela de informações.</td>
  </tr>
  <tr>
    <td class="tg-f189" rowspan="18">E02 - Usuário doador</td>
    <td class="tg-vxga" rowspan="4">FE07 - Cadastro e autenticação</td>
    <td class="tg-vxga">US18</td>
    <td class="tg-vxga">Eu, como usuário doador, gostaria de me cadastrar no Doarti, para poder fazer doações</td>
    <td class="tg-vxga">Usuário deve fornecer e-mail, nome e senha.</td>
  </tr>
  <tr>
    <td class="tg-y0n7">US19</td>
    <td class="tg-y0n7"><span style="color:#000">Eu, como usuário doador, gostaria de realizar meu login a partir do meu cadastro, para ver minhas informações</span></td>
    <td class="tg-y0n7"><span style="color:#000">Usuário deve fornecer e-mail e senha válidos.</span></td>
  </tr>
  <tr>
    <td class="tg-vxga">US20</td>
    <td class="tg-vxga"><span style="color:#000">Eu, como usuário doador, gostaria de realizar meu login pelo Facebook ou Google, para não precisar criar outra conta</span></td>
    <td class="tg-vxga"><span style="color:#000">Ter botão para entrar com redes sociais. <br />Requisitar dados das redes sociais. <br />Salvar token das redes no banco de dados.</span></td>
  </tr>
  <tr>
    <td class="tg-y0n7">US21</td>
    <td class="tg-y0n7"><span style="color:#000">Eu, como usuário doador, gostaria de realizar meu logout, para ter controle de quais dispositivos tem acesso à minha conta</span></td>
    <td class="tg-y0n7"><span style="color:#000">Ter botão para se desconectar.</span></td>
  </tr>
  <tr>
    <td class="tg-vxga" rowspan="3">FE08 - Perfil</td>
    <td class="tg-vxga">US22</td>
    <td class="tg-vxga"><span style="color:#000">Eu, como usuário doador, gostaria de visualizar meus dados do perfil, para confirmar se estão corretos</span></td>
    <td class="tg-vxga"><span style="color:#000"></span></td>
  </tr>
  <tr>
    <td class="tg-y0n7">US23</td>
    <td class="tg-y0n7">Eu, como usuário doador, gostaria de editar meus dados do perfil, para mantê-los atualizados</td>
    <td class="tg-y0n7">Botão na tela de perfil para editar dados. <br /> Tela com dados cadastrais. <br /> Caixa de edição nos dados para editá-los. <br /> Botão para salvar os novos dados.</td>
  </tr>
  <tr>
    <td class="tg-vxga">US24</td>
    <td class="tg-vxga">Eu, como usuário doador, gostaria de alterar minha senha, para manter minha conta segura</td>
    <td class="tg-vxga">Ter botão de edição de senha na tela de perfil. <br /> Enviar e-mail com instruções de alteração de senha.</td>
  </tr>
  <tr>
    <td class="tg-vxga" rowspan="2">FE09 - Selecionar campanhas</td>
    <td class="tg-y0n7">US25</td>
    <td class="tg-y0n7">Eu, como usuário doador, gostaria de buscar por entidades, campanhas e itens para doar.</td>
  </tr>
  <tr>
    <td class="tg-vxga">US26</td>
    <td class="tg-vxga">Eu, como usuário doador, gostaria de selecionar campanhas e ler as informações a respeito delas.</td>
  </tr>
  <tr>
    <td class="tg-vxga" rowspan="3">FE10 - Doações</td>
    <td class="tg-y0n7">US27</td>
    <td class="tg-y0n7">Eu, como usuário doador, gostaria de informar que quero doar pra uma campanha.</td>
  </tr>
  <tr>
    <td class="tg-vxga">US28</td>
    <td class="tg-vxga">Eu, como usuário doador, gostaria de fornecer detalhes sobre minha doação.</td>
  </tr>
  <tr>
    <td class="tg-y0n7">US29</td>
    <td class="tg-y0n7">Eu, como usuário doador, gostaria de visualizar meu histórico de doações já realizadas e em andamento.</td>
  </tr>
  <tr>
    <td class="tg-xnem" rowspan="2">FE11 - Interagir com usuário beneficiário</td>
    <td class="tg-vxga">US30</td>
    <td class="tg-vxga">Eu, como usuário doador, gostaria de entrar em contato com o usuário beneficiário para o qual quero doar.</td>
  </tr>
  <tr>
    <td class="tg-y0n7">US31</td>
    <td class="tg-y0n7">Eu, como usuário doador, gostaria de visualizar as mensagens recebidas de usuários beneficiários.</td>
  </tr>
  <tr>
    <td class="tg-vxga" rowspan="4">FE12 - Visualizar seção sobre o app</td>
    <td class="tg-vxga">US32</td>
    <td class="tg-vxga"><span style="color:#000">Eu, como usuário doador, gostaria de ver um pequeno tutorial de como utilizar o app para doar.</span></td>
  </tr>
  <tr>
    <td class="tg-y0n7">US33</td>
    <td class="tg-y0n7"><span style="color:#000">Eu, como usuário doador, gostaria de visualizar informações sobre o Doarti.</span></td>
  </tr>
  <tr>
    <td class="tg-vxga">US34</td>
    <td class="tg-vxga">Eu, como usuário doador, gostaria de entrar em contato com a equipe do Doarti.</td>
  </tr>
  <tr>
    <td class="tg-y0n7">US35</td>
    <td class="tg-y0n7">Eu, como usuário doador, gostaria de enviar um feedback sobre o aplicativo Doarti.</td>
  </tr>
</tbody>
</table>

## Referências
* Como fazer product backlog: https://www.projectbuilder.com.br/blog/como-fazer-o-product-backlog/#:~:text=O%20Product%20Backlog%20%C3%A9%20uma,nele%20que%20o%20projeto%20come%C3%A7a


## Histórico de versões

|    Data    | Versão |           Descrição           |   Autor(es)    |
| :--------: | :----: | :---------------------------: | :------------: |
| 26/10/2020 |  1.0   |     Criação do documento      |  Aline Lermen  |
| 26/10/2020 |  1.1   |  Adição da tabela de backlog  |  Aline Lermen  |
| 27/10/2020 |  1.2   | Revisão e correção da tabela  | [Ithalo Azevedo](https://github.com/ithaloazevedo) |
| 27/10/2020 |  1.3   | Adição do texto de introdução | [Ithalo Azevedo](https://github.com/ithaloazevedo) |
| 27/10/2020 |  1.4   | Estilização da tabela | [Ithalo Azevedo](https://github.com/ithaloazevedo) |
| 30/11/2020 |  1.5   | Adoção do padrão de US "Como X quero Y para Z" e adição de critérios de aceite | [Marcos Cabeceira](https://github.com/Foxtrot40) |