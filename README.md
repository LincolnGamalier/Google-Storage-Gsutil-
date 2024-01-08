# Google-Storage-Gsutil-
GCP

Debian - Ubuntu 
**Instalação do  GCP SDK em distribuições Debian/Ubuntu**

Repositórios Extra, e dependências e instalação do SDK.

$ echo "deb [signed-by=/usr/share/keyrings/cloud.google.gpg] https://packages.cloud.google.com/apt cloud-sdk main" | sudo tee -a /etc/apt/sources.list.d/google-cloud-sdk.list
$ sudo apt-get install apt-transport-https ca-certificates gnupg
$ curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key --keyring /usr/share/keyrings/cloud.google.gpg add -
$ sudo apt-get update && sudo apt-get install google-cloud-sdk
$ gcloud init

**O comando gsutil help pode ajudar nas possibilidades que o comando traz**

Para configurar o utilitário, utilizei o comando gsutil config.

![image](https://github.com/LincolnGamalier/Google-Storage-Gsutil-/assets/155745584/e890e6c1-acd5-4808-b0b4-f25970f6429b)

Projeto criado, dentro do GCP.
![image](https://github.com/LincolnGamalier/Google-Storage-Gsutil-/assets/155745584/507a9e33-416b-4998-8a46-21e478c456bb)
