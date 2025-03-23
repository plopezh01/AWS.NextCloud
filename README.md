# AWS.NextCloud

## Descripción
Scripts para lanzar automáticamente una estructura con Nextcloud y MariaDB en AWS.

## Pasos para la implementación
### Requisitos previos
- Tener **AWS CLI** correctamente configurado.

### Pasos
1. Ejecutar el script `vpc_and_private_ec2_public_ec2.ps1` desde PowerShell para crear la infraestructura en AWS.
2. Una vez creada la estructura, ejecutar `NextcloudInstallation.sh` en la **subred pública**.
3. Ejecutar `MariaDBdatabaseCreation.sh` para configurar la base de datos.

La estructura estará completamente creada y configurada con una base de datos lista para su uso.

> **IMPORTANTE:** Recuerda cambiar los datos necesarios para la **personalización**.

---

## English Version

### AWS.NextCloud

### Description
Scripts to automatically deploy a structure with Nextcloud and MariaDB on AWS.

### Deployment Steps
#### Prerequisites
- Ensure **AWS CLI** is properly configured.

#### Steps
1. Run the script `vpc_and_private_ec2_public_ec2.ps1` from PowerShell to create the AWS infrastructure.
2. Once the structure is created, execute `NextcloudInstallation.sh` in the **public subnet**.
3. Run `MariaDBdatabaseCreation.sh` to set up the database.

The structure will be fully deployed and configured with a working database.

> **IMPORTANT:** Remember to modify necessary data for **customization**.

---

### Repositorio del Co-Creador
Repositorio de **Steven Centenos**, co-creador de esta estructura: [GitHub Repository](https://github.com/scentenod2401/AWS-Nextcloud-y-AWS-CLI/tree/main)


