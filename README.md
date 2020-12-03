# Orangehrm_tool

Here volume was stored in hosting server at var folder.

    volumes:
      - '/var/ta_hrm_tool/orangehrm_data:/bitnami'

build command is: docker-compose up -d

# Environment variables

The OrangeHRM instance can be customized by specifying environment variables on the first run. The following environment values are provided to custom OrangeHRM:
User and Site configuration

    ORANGEHRM_USERNAME: OrangeHRM application username. Default: admin
    ORANGEHRM_PASSWORD: OrangeHRM application password. Default: Bitnami.12345

