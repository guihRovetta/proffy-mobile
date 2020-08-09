<h2 align="center">
Proffy - Plataforma de estudos online
<br/>
<br/>
<img src="./src/assets/images/landing.png" width="50%">
<br/>

<br/>
<div>
<img src="./src/assets/videos/proffy-mobile-demo.gif" width="50%">
</div>
<br/>

</h2>

<blockquote align="center">
  Projeto realizado durante a Next Level Week #02 da Rocketseat
</blockquote>

<hr/>

## :ballot_box_with_check: Objetivos:

Eu desenvolvi esse projeto durante a Next Level Week #02 da Rocketseat, com o intuito de reforçar meus conhecimentos na stack React, React Native e NodeJS.

## :book: Sobre:

Já na versão mobile da aplicação, na tela inicial, o usuário pode acessar Dar aulas porém até o momento ela só exibe um informativo de que deve ser cadastrado na plataforma web.

Ao acessar a opção Estudar, o usuário deve clicar no botão de filtro no canto superior direito da aplicação, a partir disso ele pode informar a matéria, o dia da semana e o horário em que ele deseja ter a aula. Nesse momento, a aplicação mostrará todos os professores disponíveis com aqueles requisitos.

O usuário ao ver o card do professor, pode adicionar o mesmo aos seus favoritos e verificar na aba na parte inferior todos seus favoritos, ou pode entrar em contato com o mesmo via WhatsApp.

## 🎓 Aplicação de conhecimentos:

- Reforço de conhecimentos sobre o React Native
- Desenvolvimento do app com o Expo
- Utilização dos hooks (useState e useEffect)
- Uso do TypeScript
- Navegação de rotas com react-navigation/native (stack e bottom-tab)
- Realização de chamadas na API com a lib axios
- Utilização do AsyncStorage
- Inclusão de fontes externas


## 🚀 Tecnologias:

- React Native
- TypeScript

## 🖥️ Como executar:

Clone o repositório com:

```bash
git clone https://github.com/guihRovetta/proffy-mobile.git
```

Para baixar as dependências e instalar, utilize o comando na raiz do projeto:

```bash
yarn
```

Para executar o projeto com esse comando, é necessário ter o expo instalado no seu dispositivo móvel e escanear o QR code que irá aparecer quando o projeto terminar de ser executado:

```bash
yarn start
```

Caso você opte pelo emulador do Android e tenha o mesmo no seu computador, rode:

```bash
yarn android
```

Se você estiver em um MacOS, pode também usar o emulador do iOS e executar o seguinte comando:

```bash
yarn ios
```

Por último, você pode também visualizar o resultado no seu navegador web e simular um dispositivo móvel, utilizando a DevTools, porém acredito que seja o menos aconselhável no processo de desenvolvimento caso queira realmente observar o funcionamento mais próximo do real possível que o app vai ter, para isso execute o comando:

```bash
yarn web
```

Lembrando que para poder salvar e acessar os dados do servidor, o projeto do back-end deve já estar rodando em sua máquina. Vale a pena notar também que nessa aplicação está sendo utilizada a porta <strong>3333</strong> do <strong>locahost</strong>. 

No arquivo <code>src/services/api.ts</code>, você encontra a URL que deve ser o mesmo valor do Connection (LAN) quando você rodar o projeto, tirando é claro o valor da porta que deve corresponder a do servidor.

## :new: Novas funcionalidades:

- [ ] Novo layout de algumas páginas
- [ ] Autenticação de usuários
- [ ] Recuperação de senhas
- [ ] Exibição e edição de perfil do professor
- [ ] Paginação na listagem de professores
- [ ] Exibição de horários disponíveis dos professores (novo layout)
- [ ] Salvar professores favoritos
- [ ] Logout da aplicação
- [ ] Deploy da aplicação

---

<h3 align="center">
Autor: <a alt="Guilherme Rovetta" href="https://github.com/guihRovetta">Guilherme Rovetta</a>
</h3>

<p align="center">

  <a alt="Guilherme de Almeida Rovetta Linkedin" href="https://www.linkedin.com/in/guilherme-rovetta-381a89b0">
  <img src="https://img.shields.io/badge/LinkedIn-Guilherme%20Rovetta-blue?logo=linkedin"/></a>
  <a alt="Guilherme de Almeida Rovetta GitHub" href="https://github.com/guihRovetta">
  <img src="https://img.shields.io/badge/GitHub-guihRovetta-lightgrey?logo=github"/></a>

</p>