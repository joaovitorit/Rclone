# CONFIGURAÇÕES DO RCLONE

* INSTALAÇÃO DO RCLONE

apt-get install -y rclone

* COPIANDO ARQUIVO LOCAL PARA O GOOGLE DRIVER

rclone copy NOMEDOCARQUIVOLOCAL Gdriver:Nomedapastanogoogledriver

* SINCRONIZAR PASTA LOCAL PARA O GOOGLE DRIVER

rclone sync NOMEDAPASTLOCAL/ Gdriver:Nomedapastanogoogledriver
