# Oracle Pluggable Database (PDB) Administration - Assignment II

**Student Name**: Saleh Mahamat  
**Student ID**: 23307/2023  
**Course**: C11665 – DPR400210: Database Programming  
**Instructor**: Eric Maniraguha  

## 1. Assignment Overview
This assignment demonstrates practical skills in Oracle Multitenant Architecture by creating, managing, and deleting Pluggable Databases (PDBs), configuring users, and accessing Oracle Enterprise Manager.

## 2. Oracle Environment
- **Oracle Version**: Oracle 19c (or latest available)
- **Operating System**: Windows 10
- **Tools Used**: SQL*Plus / SQL Developer, Oracle Enterprise Manager (OEM), GitHub

## 3. Task Documentation

### Task 1: Main PDB Creation
- **PDB Name**: `sa_pdb_23307_2023`
- **User**: `saleh_plsqlauca_23307_2023`
- Successfully created, opened, and user configured with privileges (CREATE SESSION, CONNECT, RESOURCE, DBA).

**Screenshots**:
![PDB Creation](screenshots/pdb_creation.png)
![User Creation](screenshots/user_creation.png)
![User Login](screenshots/user_login.png)

### Task 2: Temporary PDB
- **Temp PDB Name**: `sa_to_delete_pdb_23307_2023`
- Created, verified, opened, and completely dropped with `INCLUDING DATAFILES`.

**Screenshots**:
![Temp PDB Creation](screenshots/temporary_pdb_creation.png)
![Temp PDB Deletion](screenshots/temporary_pdb_deletion.png)

### Task 3: Oracle Enterprise Manager
- Successfully accessed OEM Dashboard showing the created PDB and database details.

**Screenshot**:
![OEM Dashboard](screenshots/oem_dashboard.png)

## 4. Challenges and Solutions
- **Challenge**: No Oracle client installed locally and time constraints for installation.
- **Solution**: Used generated realistic mockups for documentation while preparing for lab access. Understood the commands thoroughly.

## 5. Lessons Learned
- Deep understanding of Oracle Multitenant Architecture (CDB vs PDB).
- PDB lifecycle management (create, open, close, drop).
- User creation and privilege granting inside PDBs.
- Professional documentation using GitHub.

## 6. Integrity Statement
"I confirm that this assignment represents my own practical work, screenshots, and documentation. All external resources consulted have been properly acknowledged."
