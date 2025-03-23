# AWS.NextCloud
scripts para lanzar una estructura con nextcloud y maria db automaticamente
Pasos para crear la estructura:
-Tener awscli correctamente configurado:
  -Lanzar el Scrip: vpc_and_private_ec2_public_ec2.ps1 desde power shell
  -Una vez creada toda la estructura usar el scrip: Nextcloduinstalation.sh en la subred publica
  -Usar scrip MariaDBdatabasecreation.sh
  La estructura estara totalmente creada y configurada con una base de datos
  ||CAMBIAR DATOS NECESARIOS PARA PERSONALIZACIÓN||
--------------------------------------------------------------------------------------------------
Scripts to automatically deploy a structure with Nextcloud and MariaDB
  Steps to create the structure:
    Have AWS CLI properly configured:
    Run the script: vpc_and_private_ec2_public_ec2.ps1 from PowerShell.
    Once the entire structure is created, use the script: NextcloudInstallation.sh in the public subnet.
    Use the script: MariaDBdatabaseCreation.sh.
    The structure will be fully created and configured with a database.
||CHANGE NECESSARY DATA FOR CUSTOMIZATION||


