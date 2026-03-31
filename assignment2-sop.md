# 🖥️ Standard Operating Procedure (SOP)
## Virtual Machine Creation using VMware vSphere

---

### 📌 Company Information
**Company Name:** MITT Lab Environment  
**Location:** Winnipeg, Canada  
**Department:** IT Infrastructure  
**Version:** 2.0  
**Date:** March 30, 2026  

---

## 🎯 1. Purpose
This SOP provides a standardized and structured process for creating Virtual Machines (VMs) using VMware vSphere. It ensures consistency, reduces configuration errors, and improves operational efficiency in IT environments.

---

## 🌐 2. Scope
This document applies to:
- System Administrators  
- IT Support Staff  
- Students working in lab environments  

### Objectives:
- Ensure reliable VM deployment  
- Maintain standard configurations  
- Enhance system performance and security  

---

## 👥 3. Accountability Matrix

| Task | Responsible | Approval |
|------|------------|----------|
| Requirement Analysis | System Administrator | IT Manager |
| VM Configuration | Virtualization Team | IT Ops Manager |
| OS Installation | System Administrator | IT Manager |
| Testing & Validation | QA Team | QA Manager |
| Documentation | IT Team | Supervisor |

---

## 📖 4. Definitions

- **Virtual Machine (VM):** A software-based computer system  
- **ISO File:** OS installation file  
- **vSphere:** VMware platform for managing VMs  
- **Datastore:** Storage location for VM files  
- **vCenter:** Central management tool for VMware  

---

## ⚙️ 5. Procedure Steps

### 🔹 Step 1: Pre-Creation Planning
- Identify VM purpose (web server, database, etc.)  
- Define hardware requirements:
  - CPU cores  
  - RAM  
  - Disk space  
- Check host capacity  
- Confirm requirements with stakeholders  

---

### 🔹 Step 2: Virtual Machine Configuration
1. Open **VMware vSphere Client**  
2. Connect to **vCenter Server**  
3. Right-click → Select **New Virtual Machine**  
4. Enter:
   - VM Name  
   - Location  
   - Guest OS  
5. Allocate:
   - CPU  
   - Memory  
6. Configure:
   - Network adapter  
   - Datastore  

---

### 🔹 Step 3: Operating System Installation
- Attach ISO file  
- Power on VM  
- Follow installation steps  
- Configure:
  - Username & password  
  - Time zone  
  - Network (IP, DNS)  

---

### 🔹 Step 4: Verification & Testing
- Verify OS installation  
- Check system performance  
- Test:
  - Network connectivity  
  - Application functionality  
- Apply security updates  

---

### 🔹 Step 5: Documentation
- Record VM details:
  - Name  
  - IP Address  
  - Configuration  
- Save in system records  
- Share with team  

---

## ⚠️ 6. Risks and Mitigation

| Risk | Impact | Mitigation |
|------|--------|-----------|
| Incorrect resource allocation | Poor performance | Proper planning |
| Network misconfiguration | Connectivity failure | Verify settings |
| Security vulnerabilities | Data risk | Apply updates |

---

## 🔗 7. References
- VMware vSphere Official Documentation  
- MITT Lab Manual  
- Course Materials  

---

## 🔄 8. Revision History

| Version | Date | Changes |
|--------|------|--------|
| 1.0 | Initial | Created SOP |
| 2.0 | March 30, 2026 | Improved formatting and details |

---

## 📊 9. VM Creation Workflow Diagram

```mermaid
flowchart TD
A[Start] --> B[Planning]
B --> C[Configure VM]
C --> D[Install OS]
D --> E[Test & Verify]
E --> F[Documentation]
F --> G[End]
