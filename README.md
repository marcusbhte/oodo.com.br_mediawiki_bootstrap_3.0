# oodo.com.br_mediawiki_bootstrap_3.0
Tema mediawiki para o site oodo.com.br
inspirado e baseado no tema: https://github.com/borkweb/bootstrap-mediawiki



<hr>


# Bootstrap Mediawiki

Esta é uma customização para MediaWiki que usa Bootstrap 3. 
A instalação é bastante simples, use por sua conta e risco, teste antes de colocar em produção.

Em breve colocaremos à disposição um exemplo.

## Instalação
Primeiro, clone o repositorio em seu diretório `skins/`.

```
git clone https://github.com/borkweb/bootstrap-mediawiki.git
```
Depois faça um backup de seu arquivo `LocalSettings.php` para `LocalSettings.bak.php`,
Depois vamos alterar a variável no arquivo`LocalSettings.php`:

```php
$wgDefaultSkin = 'bootstrap_by_oodo';
```

Em seguida adicione logo abaixo:

```php
require_once( "$IP/skins/bootstrap_by_oodo/bootstrap_by_oodo.php" );
```
