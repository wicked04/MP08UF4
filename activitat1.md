# Enunciat:

Documenteu la instal·lació de Moodle a la vostra Màquina Virtual.

- Explicar els passos seguits durant la instal·lació de Moodle (4 punts).
  -   Instal·lació APACHE (1p).
  -   Primerament instalarem el apache en la comanda: 
  -   sudo apt-get install apache2
  -   Instal·lació BBDD (1p).
  -   Per install el BBDD, he decidit de install MySQL, amb les seguents comandes: 
  -   sudo apt-get install mysql-server
  -   sudo mysql -u root -p
  -   Instal·lació PHP (1p).
  -   Per installar el PHP, seran 3 comandes: 
  -   sudo apt -y install software-properties-common
  -   sudo add-apt-repository ppa:ondrej/php 
  -   sudo apt install libapache2-mod-php7.4 php7.4-mysql. ''7.4'' es la versio que correspon al PHP
  -   Instal·lació Moodle (1p).
  -   Per fer la installacio i configuracio de Moodle hi han varies comandes a escriure:
  -  Primerament em de buscar el arixiu de instalacio a la pagina web del moodle y fcar-ho al terminal, despres        en la comanda unzip, la descomprimerem.
  -  Dintre de /var/ww/html escriurem la comanda sudo mysql -u root -p.
  -  Continuadament instalarem el el curl y el zip del php y reiniciarem el apache2
  -  Configurarem el ficher config.php y per ultim instaler un requisits del php
  -   
- Inserir les captures de pantalla dels moments delicats de la instal·lació, explicant què es fa a la captura (4 punts).
  -   Instal·lació APACHE (1p).
  -   ![image](https://user-images.githubusercontent.com/114423260/207095733-61712ede-b869-409d-8897-b70a43464758.png)
  -   ![image](https://user-images.githubusercontent.com/114423260/204332272-526246f0-42f4-4ef6-ac4a-6e6362d8f90a.png)

  -   Instal·lació BBDD (1p).
  -  ![image](https://user-images.githubusercontent.com/114423260/207097221-2688ac96-51f2-4c73-a5de-5e48d5071da8.png)
  -  ![image](https://user-images.githubusercontent.com/114423260/207098244-b8cace71-3b2b-4587-b89e-eaaf44184561.png)


  -   Instal·lació PHP (1p).
      ![image](https://user-images.githubusercontent.com/114423260/207113916-b181db25-f0b9-4639-ba1c-b79091d3be0d.png)
      ![image](https://user-images.githubusercontent.com/114423260/207114260-c37fb6cd-0979-4a33-be3d-e711cfe94488.png)
      ![image](https://user-images.githubusercontent.com/114423260/207114339-18b3d507-58f1-4d57-a7f7-a0c796b4934b.png)


  -   Instal·lació Moodle (1p).
  -   ![image](https://user-images.githubusercontent.com/114423260/207122756-7ae37335-6176-4a4e-8ed3-ea6f0962d3f2.png)

  -  ![image](https://user-images.githubusercontent.com/114423260/207118261-febb1c7c-0a2a-408b-a2a0-6132d46a3713.png)
    
   ![image](https://user-images.githubusercontent.com/114423260/207124475-06679882-78fc-4664-a8cc-e4f28ce30ce4.png)
   
 ![image](https://user-images.githubusercontent.com/114423260/208088122-9e2d11c3-d65a-4cd1-8d1b-2d15bc95c3b1.png)
 
 ![Selección_150](https://user-images.githubusercontent.com/114423260/208088992-6fdc9ce8-1c8f-4f52-9d69-7f24c82f5fcf.png)

 ![image](https://user-images.githubusercontent.com/114423260/208089175-7f4271d2-a73f-467c-94c6-311cb24eec6f.png)
 ![image](https://user-images.githubusercontent.com/114423260/208477410-aa425ad8-b5bd-4e32-8d7c-064b70653dd1.png)
![image](https://user-images.githubusercontent.com/114423260/208477448-b6c6ed36-7ecd-4813-bc05-c2809ae696f3.png)
![image](https://user-images.githubusercontent.com/114423260/208477480-460004fd-e1d3-4683-8878-21855907ee85.png)
![image](https://user-images.githubusercontent.com/114423260/208477521-b7941079-fc37-4c57-9e58-7c64fbddbfb9.png)
![image](https://user-images.githubusercontent.com/114423260/208489425-e3e0af2e-f9c0-422c-8444-849737e570aa.png)

 


- Documentar els problemes que hem tingut durant la instal·lació (2 punts).
  -   Com hem sapigut quina versió de PHP instal·lar (1p).
  -   Altres (1p).
