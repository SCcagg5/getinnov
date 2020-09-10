# Wellcheck

## Launch the project

**In order to run the project using localhost, create :**

- `.env` file:
  * Path: `#docker-compose/`
  * Content :
    ```bash
    API_MOD=DEV
    #API DEBUG MOD

    DOMAIN=localhost
    #the domain your deploying on

    EMAIL=eliot.courtel@wanadoo.fr
    #a mail to be used in let's encrypt
    ```
**You're ready to deploy the infrastructure**

* ```bash
  cd \#docker-compose/; \
  docker-compose -f docker-compose.reverse.proxy.yml      up -d; \
  docker-compose -f docker-compose.getinnov.web.yml      up -d; \
  docker-compose -f docker-compose.getinnov.services.yml up -d;
  ```

**You can know use the landing page properly !**
