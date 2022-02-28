# Installation du serveur Apache 

### 1 - Sous Fedora/CentOS/Red Hat Enterprise Linux
    Ici nous allons installer Apache HTTPD sur Fedora : 
 * Installation des packages HTTPD : 
    ```sh
        sudo dnf installer httpd -y
     ```

 * Démarrage du service HTTPD : 
    ```sh
        sudo systemctl démarrer httpd.service
    ```