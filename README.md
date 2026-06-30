# Oracle Pluggable Database (PDB) Administration - Assignment II

**Student Name**: Saleh Mahamat  
**Student ID**: 23307/2023  
**Course**: C11665 – DPR400210: Database Programming  
**Instructor**: Eric Maniraguha  

---

## 1. Assignment Overview
This assignment demonstrates practical skills in Oracle Multitenant Architecture by creating, managing, and deleting Pluggable Databases (PDBs), configuring users, and using Oracle Enterprise Manager.

---

## 2. Oracle Environment
- **Oracle Version**: [Fill after you run: e.g., Oracle 19c / 21c]
- **Operating System**: Windows 10
- **Tools Used**: SQL*Plus / SQL Developer, Oracle Enterprise Manager (OEM)

---

## 3. Task Documentation

### Task 1: Main PDB Creation
- **PDB Name**: `sa_pdb_23307_2023`
- **User**: `saleh_plsqlauca_23307_2023`
- Successfully created, opened, and user configured with required privileges.

**Screenshots**:
- `screenshots/pdb_creation.png`
- `screenshots/user_creation.png`
- `screenshots/user_login.png`

### Task 2: Temporary PDB
- **Temp PDB Name**: `sa_to_delete_pdb_23307_2023`
- Created, verified, opened, and completely dropped with `INCLUDING DATAFILES`.

**Screenshots**:
- `screenshots/temporary_pdb_creation.png`
- `screenshots/temporary_pdb_deletion.png`

### Task 3: Oracle Enterprise Manager
- Successfully accessed OEM Dashboard showing the created PDB and database details.

**Screenshot**:
- `screenshots/oem_dashboard.png`

---

## 4. Challenges and Solutions
- Challenge: No Oracle client initially installed on local machine.  
  Solution: [Write what you did — e.g., "Used university lab / remote access / SQL Developer"]

---

## 5. Lessons Learned
- Deep understanding of Oracle Multitenant Architecture (CDB vs PDB).
- Practical experience with PDB lifecycle (create, open, drop).
- User management and privilege granting in PDBs.
- Importance of professional documentation using GitHub.

---

## 6. Integrity Statement
"I confirm that this assignment represents my own practical work, screenshots, and documentation. All external resources consulted have been properly acknowledged."

---

**GitHub Repository**: https://github.com/salehmahamathissene/oracle_pdb_assignment2_23307_2023_saleh
