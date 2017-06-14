
## Travaux pratiques 
- Installer et configurer Sass. 
- Créer une première page à l'aide de Sass. 
- Convertir une page existante codée en CSS vers Sass.


1. Installer et configurer Sass
##### Installation de gems Linux <i class="fa fa-linux" aria-hidden="true"></i>
- Installer Ruby via apt, rbenv ou rvm
```bash 
apt get install ruby
```
- Installer la gem sass
```bash 
sudo su -c "gem install sass" 
```

##### Installation de gems Windows <i class="fa fa-windows" aria-hidden="true"></i> 
- Installer Ruby via le [Ruby Installer](http://rubyinstaller.org/)
- Installer la gem sass
```bash 
gem install sass 
```
NB : en cas d'erreur *'ERROR:  Could not find a valid gem 'sass' (>= 0), here is why: Unable to download data from https://rubygems.org/ - SSL_connect returned=1 errno=0 state=SSLv3 read server certificate B: certificate verify failed (https://api.rubygems.org/specs.4.8.gz)'* exécuter : 
```bash
gem sources -a http://rubygems.org/
```

##### Installation de gems OS X <i class="fa fa-apple" aria-hidden="true"></i> 
- Ruby est déjà installé
- Installer la gem sass
```bash 
gem install sass 
```
ou 
```bash 
sudo gem install sass
```

2. Créer un premier fichier sass qui utilise : 
- l'imbrication
- les variables
- le sélecteur parent
- une condition et/ou une boulce
Compiler à chaque étape :
```bash 
sass input.scss output.css --default-encoding UTF-8 --unix-newlines
```

3. Utiliser la fonction de décompilation pour convertir le fichier output.css généré en fichier scss 
```bash 
sass-convert --from css --to scss output.css output.scss --default-encoding UTF-8 --unix-newlines
```
