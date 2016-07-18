# was.ci

# Pré-requisitos
Instalar os seguintes pré-requisitos:

1. Jenkins
2. Plugin WebSphere Deployer (https://wiki.jenkins-ci.org/display/JENKINS/WebSphere+Deployer+Plugin)
  1. Os arquivos com.ibm.ws.admin.client_*.jar e com.ibm.ws.orb_*.jar estão dentro do WebSphere Application Server Client v8.5.5 (Utilizar IBM Installation Manager e apontar para repositório 	http://www.ibm.com/software/repositorymanager/com.ibm.websphere.APPCLIENTILAN.v85)

# Procedimento
1. Dentro do Jenkins criar um "Freestyle project"
2. Na etapa "Criar Build Step" do tipo "Deploy to WebSphere Application Server"
