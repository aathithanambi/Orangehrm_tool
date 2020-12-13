# Orangehrm_tool

Here volume is stored in the hosting server at var folder. So the data stored will not delete if container stopped or crashed. 
We need to create the folder inside the var folder.

    volumes:
      - '/var/hrm_tool/orangehrm_data:/bitnami'
      - '/var/hrm_tool/mariadb_data:/bitnami'

Build command is: sudo docker-compose up -d

# Environment variables

The OrangeHRM instance can be customized by specifying environment variables on the first run. The following environment values are provided to custom OrangeHRM:
User and Site configuration

    ORANGEHRM_USERNAME: OrangeHRM application username. Default: admin
    ORANGEHRM_PASSWORD: OrangeHRM application password. Default: Bitnami.12345

