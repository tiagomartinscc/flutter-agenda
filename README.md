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






## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
