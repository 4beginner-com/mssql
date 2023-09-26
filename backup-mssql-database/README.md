# mssql

## Backup MSSQL Database

Use the provided script to backup your MSSQL database:
[backup-mssql-database/backupbat.bat](https://github.com/4beginner-com/mssql/blob/main/backup-mssql-database/backupbat.bat)

You can execute the above script to backup the database from the command prompt using `sqlpackage`.

### Prerequisite: SqlPackage.exe

If `sqlpackage` is not available on your system, follow the steps below:

#### 1. Download & Install the Dac Framework (DacFx)
- Visit the [official Microsoft download page for the Data-Tier Application Framework (DacFx)](https://docs.microsoft.com/en-us/sql/tools/sqlpackage-download?view=sql-server-ver15).
- Choose the appropriate version for your platform (e.g., Windows 64-bit) and download.
- Install the DacFx. After the installation, `SqlPackage.exe` should be available at a location similar to: `C:\Program Files (x86)\Microsoft SQL Server\<version>\DAC\bin`.
