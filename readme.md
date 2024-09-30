# BookStack

[![GitHub release](https://img.shields.io/github/release/BookStackApp/BookStack.svg)](https://github.com/BookStackApp/BookStack/releases/latest)
[![license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/BookStackApp/BookStack/blob/development/LICENSE)
[![Crowdin](https://badges.crowdin.net/bookstack/localized.svg)](https://crowdin.com/project/bookstack)
[![Build Status](https://github.com/BookStackApp/BookStack/workflows/test-php/badge.svg)](https://github.com/BookStackApp/BookStack/actions)
[![Lint Status](https://github.com/BookStackApp/BookStack/workflows/lint-php/badge.svg)](https://github.com/BookStackApp/BookStack/actions)
[![Maintainability](https://api.codeclimate.com/v1/badges/5551731994dd22fa1f4f/maintainability)](https://codeclimate.com/github/BookStackApp/BookStack/maintainability)

[![Alternate Source](https://img.shields.io/static/v1?label=Alt+Source&message=Git&color=ef391a&logo=git)](https://source.bookstackapp.com/)
[![Repo Stats](https://img.shields.io/static/v1?label=GitHub+project&message=stats&color=f27e3f)](https://gh-stats.bookstackapp.com/)
[![Discord](https://img.shields.io/static/v1?label=Discord&message=chat&color=738adb&logo=discord)](https://discord.gg/ztkBqR2)
[![Mastodon](https://img.shields.io/static/v1?label=Mastodon&message=@bookstack&color=595aff&logo=mastodon)](https://fosstodon.org/@bookstack)

[![PeerTube](https://img.shields.io/static/v1?label=PeerTube&message=bookstack@foss.video&color=f2690d&logo=peertube)](https://foss.video/c/bookstack)
[![YouTube](https://img.shields.io/static/v1?label=YouTube&message=bookstackapp&color=ff0000&logo=youtube)](https://www.youtube.com/bookstackapp)

Uma plataforma para armazenar e organizar informações e documentação, seja informações de Jogos, domucentos de empresas e muitas outras coias. Detalhes do BookStack podem ser encontrados no site oficial em: https://www.bookstackapp.com/.

* [Instruções de Instalaçõa](https://www.bookstackapp.com/docs/admin/installation)
* [Documentação](https://www.bookstackapp.com/docs)
* [Instacia de demonstração](https://demo.bookstackapp.com)
    * [Admin Login](https://demo.bookstackapp.com/login?email=admin@example.com&password=password)
* [Capturas de tela](https://www.bookstackapp.com/#screenshots) 
* [BookStack Blog](https://www.bookstackapp.com/blog)
* [Issue List](https://github.com/BookStackApp/BookStack/issues)
* [Discord Chat](https://discord.gg/ztkBqR2)
* [Opções de Suporte](https://www.bookstackapp.com/support/)

  Obs.: A documentação base está em ingles.

## 📚 Definição de Projeto

BookStack é uma plataforma de documentação opinativa que oferece uma experiência agradável, simples e pronta para uso. Os novos usuários de uma instância devem achar a experiência intuitiva e apenas habilidades básicas de processamento de texto devem ser necessárias para se envolver na criação de conteúdo no BookStack.
A plataforma deve fornecer recursos avançados de energia para aqueles que os desejam, mas não devem interferir na experiência simples do usuário.

BookStack não foi projetado como uma plataforma extensível para ser usada para propósitos diferentes da afirmação acima.

No que diz respeito à filosofia de desenvolvimento, BookStack tem uma abordagem descontraída, aberta e positiva. No final das contas, este é um software livre desenvolvido e mantido por pessoas que doam seu próprio tempo livre.

Você pode ler mais sobre o projeto e suas origens em [our FAQ here](https://www.bookstackapp.com/about/project-faq/).


## 🛠️ Desenvolvimento e Teste

Consulte os [documentos de desenvolvimento](dev/docs/development.md) para obter detalhes completos sobre o trabalho no código-fonte do BookStack.

Se você deseja apenas personalizar ou estender sua própria instância do BookStack, dê uma olhada em [página de documentação do Hacking BookStack](https://www.bookstackapp.com/docs/admin/hacking-
bookstack/) para obter detalhes sobre várias opções para conseguir isso sem alterar o código-fonte do BookStack.

Detalhes sobre o esquema de versionamento do BookStack e o processo geral de lançamento [podem ser encontrados aqui](dev/docs/release-process.md).

## 🌎 Translations

Translations for text within BookStack is managed through the [BookStack project on Crowdin](https://crowdin.com/project/bookstack). Some strings have colon-prefixed variables such as `:userName`. Leave these values as they are as they will be replaced at run-time.

Please use [Crowdin](https://crowdin.com/project/bookstack) to contribute translations instead of opening a pull request. The translations within the working codebase can be out-of-date, and merging via code can cause conflicts & sync issues. If for some reason you can't use Crowdin feel free to open an issue to discuss alternative options. 

If you'd like a new language to be added to Crowdin, for you to be able to provide translations for, please [open a new issue here](https://github.com/BookStackApp/BookStack/issues/new?template=language_request.yml).

Please note, translations in BookStack are provided to the "Crowdin Global Translation Memory" which helps BookStack and other projects with finding translations. If you are not happy with contributing to this then providing translations to BookStack, even manually via GitHub, is not advised.

## 🎁 Contributing, Issues & Pull Requests

Feel free to [create issues](https://github.com/BookStackApp/BookStack/issues/new/choose) to request new features or to report bugs & problems. Just please follow the template given when creating the issue.

Pull requests are welcome but, unless it's a small tweak, it may be best to open the pull request early or create an issue for your intended change to discuss how it will fit into the project and plan out the merge. Just because a feature request exists, or is tagged, does not mean that feature would be accepted into the core project.

Pull requests should be created from the `development` branch since they will be merged back into `development` once done. Please do not build from or request a merge into the `release` branch as this is only for publishing releases. If you are looking to alter CSS or JavaScript content please edit the source files found in `resources/`. Any CSS or JS files within `public` are built from these source files and therefore should not be edited directly.

The project's code of conduct [can be found here](https://github.com/BookStackApp/BookStack/blob/development/.github/CODE_OF_CONDUCT.md).

## 🔒 Security

Security information for administering a BookStack instance can be found on the [documentation site here](https://www.bookstackapp.com/docs/admin/security/).

If you'd like to be notified of new potential security concerns you can [sign-up to the BookStack security mailing list](https://updates.bookstackapp.com/signup/bookstack-security-updates).

If you would like to report a security concern, details of doing so [can be found here](https://github.com/BookStackApp/BookStack/blob/development/.github/SECURITY.md).

## ♿ Accessibility

We want BookStack to remain accessible to as many people as possible. We aim for at least WCAG 2.1 Level A standards where possible although we do not strictly test this upon each release. If you come across any accessibility issues please feel free to open an issue.

## 🖥️ Website, Docs & Blog

The website which contains the project docs & blog can be found in the [BookStackApp/website](https://github.com/BookStackApp/website) repo.

## ⚖️ License

The BookStack source is provided under the [MIT License](https://github.com/BookStackApp/BookStack/blob/development/LICENSE). 

The libraries used by, and included with, BookStack are provided under their own licenses and copyright.
The licenses for many of our core dependencies can be found in the attribution list below but this is not an exhaustive list of all projects used within BookStack. 

## 👪 Attribution

The great people that have worked to build and improve BookStack can [be seen here](https://github.com/BookStackApp/BookStack/graphs/contributors). The wonderful people that have provided translations, either through GitHub or via Crowdin [can be seen here](https://github.com/BookStackApp/BookStack/blob/development/.github/translators.txt).

Below are the great open-source projects used to help build BookStack. 
Note: This is not an exhaustive list of all libraries and projects that would be used in an active BookStack instance.

* [Laravel](http://laravel.com/) - _[MIT](https://github.com/laravel/framework/blob/v8.82.0/LICENSE.md)_
* [TinyMCE](https://www.tinymce.com/) - _[MIT](https://github.com/tinymce/tinymce/blob/develop/LICENSE.TXT)_
* [Lexical](https://lexical.dev/) - _[MIT](https://github.com/facebook/lexical/blob/main/LICENSE)_
* [CodeMirror](https://codemirror.net) - _[MIT](https://github.com/codemirror/CodeMirror/blob/master/LICENSE)_
* [Sortable](https://github.com/SortableJS/Sortable) - _[MIT](https://github.com/SortableJS/Sortable/blob/master/LICENSE)_
* [Google Material Icons](https://github.com/google/material-design-icons) - _[Apache-2.0](https://github.com/google/material-design-icons/blob/master/LICENSE)_
* [markdown-it](https://github.com/markdown-it/markdown-it) and [markdown-it-task-lists](https://github.com/revin/markdown-it-task-lists) - _[MIT](https://github.com/markdown-it/markdown-it/blob/master/LICENSE) and [ISC](https://github.com/revin/markdown-it-task-lists/blob/master/LICENSE)_
* [Dompdf](https://github.com/dompdf/dompdf) - _[LGPL v2.1](https://github.com/dompdf/dompdf/blob/master/LICENSE.LGPL)_
* [KnpLabs/snappy](https://github.com/KnpLabs/snappy) - _[MIT](https://github.com/KnpLabs/snappy/blob/master/LICENSE)_
* [WKHTMLtoPDF](http://wkhtmltopdf.org/index.html) - _[LGPL v3.0](https://github.com/wkhtmltopdf/wkhtmltopdf/blob/master/LICENSE)_
* [diagrams.net](https://github.com/jgraph/drawio) - _[Embedded Version Terms](https://www.diagrams.net/trust/) / [Source Project - Apache-2.0](https://github.com/jgraph/drawio/blob/dev/LICENSE)_
* [OneLogin's SAML PHP Toolkit](https://github.com/onelogin/php-saml) - _[MIT](https://github.com/onelogin/php-saml/blob/master/LICENSE)_
* [League/CommonMark](https://commonmark.thephpleague.com/) - _[BSD-3-Clause](https://github.com/thephpleague/commonmark/blob/2.2/LICENSE)_
* [League/Flysystem](https://flysystem.thephpleague.com) - _[MIT](https://github.com/thephpleague/flysystem/blob/3.x/LICENSE)_
* [League/html-to-markdown](https://github.com/thephpleague/html-to-markdown) - _[MIT](https://github.com/thephpleague/html-to-markdown/blob/master/LICENSE)_
* [League/oauth2-client](https://oauth2-client.thephpleague.com/) - _[MIT](https://github.com/thephpleague/oauth2-client/blob/master/LICENSE)_
* [pragmarx/google2fa](https://github.com/antonioribeiro/google2fa) - _[MIT](https://github.com/antonioribeiro/google2fa/blob/8.x/LICENSE.md)_
* [Bacon/BaconQrCode](https://github.com/Bacon/BaconQrCode) - _[BSD-2-Clause](https://github.com/Bacon/BaconQrCode/blob/master/LICENSE)_
* [phpseclib](https://github.com/phpseclib/phpseclib) - _[MIT](https://github.com/phpseclib/phpseclib/blob/master/LICENSE)_
* [Clockwork](https://github.com/itsgoingd/clockwork) - _[MIT](https://github.com/itsgoingd/clockwork/blob/master/LICENSE)_
* [PHPStan](https://phpstan.org/) & [Larastan](https://github.com/nunomaduro/larastan) - _[MIT](https://github.com/phpstan/phpstan/blob/master/LICENSE) and [MIT](https://github.com/nunomaduro/larastan/blob/master/LICENSE.md)_
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - _[BSD 3-Clause](https://github.com/squizlabs/PHP_CodeSniffer/blob/master/licence.txt)_
* [JakeArchibald/IDB-Keyval](https://github.com/jakearchibald/idb-keyval) - _[Apache-2.0](https://github.com/jakearchibald/idb-keyval/blob/main/LICENCE)_

For a detailed breakdown of the JavaScript & PHP projects imported & used via NPM & composer package managers, along with their licenses, please see the [dev/licensing/js-library-licenses.txt](dev/licensing/js-library-licenses.txt) and [dev/licensing/php-library-licenses.txt](dev/licensing/php-library-licenses.txt) files. 
