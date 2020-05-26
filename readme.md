Criado
cordova	create	garconapp	org.mk.garconapp	"Garçonete	Só	de	Cenoura"

adicionado para desenvolcer no browser
cordova	platform add browser

executa o app no nahegador
cordova	run	browser

adiocionado para desenvolver n0o android
cordova	platform add android

executa no android
cordova	run	android

gerar apk instavel
cordova	build	android

apk final
cordova	build	android	--release google play

Materialize

config xml
    <preference	name="Orientation" value="portrait"	/> trava o app numa posição em pe sempre
    <preference	name="Fullscreen" value="true"	/> tela chei por padroa vem false

    <icon	src="resources/icon.png"	/> icon
<splash	src="resources/splash.png"	/> splash

crie pasta resources
com 2 arquivos png
icon.png
splah.png e rode
ionic	init 
ionic cordova resorces
cordova	platform	save

plugins
cordova	plugin add
cordova	plugin	add	phonegap-plugin-barcodescanner --save

status bar 
cordova	plugin	add	cordova-plugin-statusbar	--save

