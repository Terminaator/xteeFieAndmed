Lahenduse kirjeldus

  Loodav rakendus on etteantud WSDL-i (services.wsdl) põhjal koostatud veebiteenus, mis sisaldab
  vastust ühele päringule.
  Lahendus ei pea täitma X-tee turvaserverist tulenevaid vajadusi, ehk teenuse päises sisalduvaid
  andmeid rakendus töötlema ei pea. Veebiteenuse poolt väljastatavad andmed võivad olla rakenduses
  staatiliselt määratud.
  
Rakunduse käivitamine lokaalselt

  Et jooksutada seda, tuleb teil alla tõmmata Tomcat https://tomcat.apache.org/download-80.cgi.
  Pärast seda "git clone https://github.com/Terminaator/xteeFieAndmed.git"
  Edasi tuleb kasutada "mvn install", mis loob Target'i alla xteeFieAndmed.war kopeerige see fail Apache tomcat webapps kausta.
  Pärast seda minge Apache tomcat bin kausta ja avage startup.sh.
  
  Endpoint address: http://localhost:8080/xteeFieAndmed/services/XteeFieAndmedSOAP
  WSDL: http://localhost:8080/xteeFieAndmed/services/XteeFieAndmedSOAP?wsdl
