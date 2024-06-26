# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-e1-proj-web-t2-ads-e1-grupo3-sabio-guia/blob/main/docs/02-Especifica%C3%A7%C3%A3o%20do%20Projeto.md"> Especificação do Projeto</a></span>, <a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-e1-proj-web-t2-ads-e1-grupo3-sabio-guia/blob/main/docs/04-Projeto%20de%20Interface.md"> Projeto de Interface</a>

Os requisitos para realização dos testes de software são:
<ul><li>Site publicado na internet;</li>
<li>Navegador da internet: Chrome</li>
</ul>

Os testes funcionais a serem realizados na aplicação são descritos a seguir.

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>

 <tr>
  <td>CT-01: Verificar o cadastro de usuários e a recuperação de senha.</td>
  <td>
   <ul>
    <li>RF-001:	Permitir ao usuário a criação da conta.</li>
   </ul>
  </td>
  <td>Verificar se a página de cadastro está funcionando corretamente.</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a página Cadastro.</li>
    <li>Preencher o formulário e clicar em "Cadastrar".</li>
   </ol>
   </td>
  <td>Deve ocorrer uma validação das informações fornecidas pelo usuário, e ao clicar em "Cadastrar", deve direcionar para a página de login.</td>
  <td>Nayara Aparecida</td>
 </tr>

<tr>
  <td>CT-02: Verificar se a página do perfil de usuario está funcional</td>
  <td>
   <ul>
    <li>RF-002:	Permitir ao usuário a edição de seu perfil no site.</li>
    <li>RF-009:	Permitir ao usuário a exclusão de sua conta.</li>
   </ul>
  </td>
  <td>Verificar se ao acessar a página de perfil é possivel escolher uma nova foto de úsuario e excluir a conta.</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Fazer login na conta.</li>
    <li>Acessar a página de perfil.</li>
    <li>Mudar a foto.</li>
    <li>Excluir a conta.</li>
   </ol>
   </td>
  <td>Após o login o úsuario deve ser capaz de mudar sua foto de perfil ou excluir a conta.</td>
  <td>Marilio César</td>
 </tr>
 
 <tr>
  <td>CT-03: Verificar o funcionamento da funcionalidade de ampliação da fonte</td>
  <td>
   <ul>
    <li>RF-003:	Permitir ao usuário ampliar a fonte no site.</li>
   </ul>
  </td>
  <td>Verificar se ao clicar nos icones A+ ou A- o tamanho da fonte é alterada.</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar as páginas</li>
    <li>Clicar nos icones A+ ou A-</li>
   </ol>
   </td>
  <td>Todas as letras devem aumentar ou diminuir de tamanho sem quebrar a responsividade.</td>
  <td>Carolina Costa</td>
 </tr>

<tr>
  <td>CT-04: Verificar se a funcionalidade de avaliar e comentar o tutorial registra a informação.</td>
  <td>
   <ul>
    <li>RF-004:	Permitir ao usuário avaliar o tutorial.</li>
    <li>RF-007:	Permitir ao usuário realizar comentários na página do tutorial.</li>
   </ul>
  </td>
  <td>Verifique se, ao clicar no botão "Enviar comentário", o comentário e a avaliação são registrados na página.</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Estar logado</li>
     <li>Acessar a página de Cursos</li>
     <li>Visualizar o curso "Como adicionar um contato no WhatsApp"</li>
      <li>Resgistrar um comentario</li>
       <li>Realizar a avaliação</li>
       <li>Clicar no botão "Enviar comentário"</li>
   </ol>
   </td>
  <td>Visualizar o registro do comentario e avalição no site</td>
  <td>Fernando Diniz</td>
 </tr>

 <tr>
  <td>CT-05: Verificar o checklist do passo a passo dos cursos.
</td>
  <td>
   <ul>
    <li>RF-005:	Permitir ao usuário realizar o checklist de passo a passo nos tutoriais.</li>
   </ul>
  </td>
  <td>Verificar se o campo de checklist está recebendo o clique de cada item do passo a passo.</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar as páginas dos cursos.</li>
    <li>Clicar em cada item realizado do passo a passo.</li>
   </ol>
   </td>
  <td>Os usuários conseguirão clicar em cada ícone de passo a passo, indicando que aquele passo foi concluído.</td>
  <td>Carolina Costa</td>
 </tr>

 <tr>
  <td>CT-06: Verificar as informações contidas na página Sobre</td>
  <td>
   <ul>
    <li>RF-006:	Permitir ao usuário acessar a página Sobre.</li>
   </ul>
  </td>
  <td>Verificar se o usuario possui acesso a página sobre</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Clique no item do menu de navegação "Sobre"</li>
   </ol>
   </td>
  <td>Todos os usuarios deverão ter acesso a página sobre para terem maiores informações sobre nosso sistema.</td>
  <td>Leonardo Costa</td>
 </tr>
 
 <tr>
  <td>CT-07: Verificar a visualização dos depoimentos dos usuários</td>
  <td>
   <ul>
    <li>RF-010:	Permitir ao usuário visualizar depoimentos dos demais usuários.</li>
   </ul>
  </td>
  <td>Verificar se os depoimentos dos usuários estão visíveis.</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Acessar a Página Inicial</li>
    <li>Rolar a página até visualizar a seção de "depoimentos dos nossos usuários"</li>
   </ol>
   </td>
  <td>Todas os depoimentos devem estar visíveis ao acessar a Página Inicial.</td>
  <td>Fernanda Sayuri</td>
 </tr>

<tr>
  <td>CT-08: Verificar a recuperação de senha.</td>
  <td>
   <ul>
    <li>RF-008:	Permitir ao usuário a recuperação de senha.</li>
   </ul>
  </td>
  <td>Verificar se a página de recuperação de senha está funcionando corretamente.</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a página Entrar.</li>
    <li>Clicar em "Esqueci minha senha".</li>
    <li>Preencher o formulário e clicar em "Confirmar".</li>
   </ol>
   </td>
  <td>Deve ocorrer uma validação das informações fornecidas pelo usuário, e ao clicar em "Confirmar", deve aparecer a mensagem "Senha alterada com sucesso".</td>
  <td>Nayara Aparecida</td>
 </tr>


 
</table>
