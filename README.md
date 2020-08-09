# flutter_agenda

Agenda de contatos com integração com camera e salvando dados em banco de dados sqlite localmente no dispositivo.

Conceitos aprendidos:

* Integração completa (crud) com SQLITE utilizando o flutter e o package "sqflite: ^1.1.5"
* Integração com o package "url_launcher: ^5.0.2" para fazer ligação pelo dispositivo.
* Integração com o package "image_picker: ^0.6.0+3" para integrar com a câmera do dispositivo.
* Widget PopupMenuButton para ordenar a lista de contatos
* FloatingActionButton para adicionar contatos e salvar (Botão flutuante no canto inferior direito do app)
* Navegação usando Navigator.push e Navigator.pop
* showModalBottomSheet para exibir opções como modal inferior (Ligar, Editar Excluir)
* MaterialPageRoute retornando conteúdo (Objeto contact)
* WillPopScope para controlar ação de voltar (perguntar se deseja sair sem salvar)

## Sobre o App

Tela inicial do App
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596996740.png" />

Agenda iniciada sem nenhum contato da primeira vez.

Ao clicar no botão adicionar no canto inferior direito o app direciona para página de cadastro do contato.

<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596996744.png" />

Título da página é o nome do contato

<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596996766.png" />

Após salvar o contato, app volta para página inicial mostrando uma lista de contatos.
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596996872.png" />

Se clicar em um contato, aparece as seguintes opções:
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596996878.png" />

Clicando em ligar, será direcionado para o telefone para ligar ou salvar o contato na agenda do telefone.
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596996883.png" />

Se clicar em Editar, poderá alterar as informações do contato.
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596996896.png" />

Clicando ia foto, abrirá a câmera do dispositivo para salvar uma foto.
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596996913.png" />

Foto salva no contato
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596996940.png" />

Se tentar sair da página sem salvar as alterações é exibido o seguinte alerta
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596997901.png" />

Após salvar a imagem é exibida na lista
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596997004.png" />

Clicando no botão superior direito é possível ordenar a lista de contatos
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596997024.png" />

Exibição em ordem alfabética (A-Z)
<img style="width: 300px" src="https://github.com/tiagomartinscc/flutter-agenda/raw/master/doc/Screenshot_1596997029.png" />































## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
