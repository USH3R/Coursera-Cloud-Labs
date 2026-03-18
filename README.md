# Coursera Cloud Lab

**Author:** Brian Dodd  
**Course:** Coursera Cloud Computing Lab  

---

## Overview

This repository contains files and scripts for a Coursera Cloud Computing lab focused on **AWS EC2 instance automation**. The lab demonstrates how to:

- Launch EC2 instances from the command line.  
- Use Bash scripts and variable files for automation.  
- Leverage Python (`boto3`) for interacting with AWS resources.  
- Organize cloud lab workflows in a structured repository.

---

## Repository Structure

| File / Folder | Purpose |
|---------------|---------|
| `lab_cloud_computing.sh` | Bash script to launch EC2 instances based on variables defined in `arguments.txt`. |
| `arguments.txt` | Text file containing EC2 instance parameters (image ID, instance type, key pair, security groups, etc.). |
| `requirements.txt` | Python dependencies for automation scripts (`boto3`, `requests`, `datetime`, `tqdm`). |
| `test_python.py` | Test script to verify Python and AWS SDK functionality. |
| `.gitignore` | Lists files/folders to be ignored by Git. |
| `README.md` | Project overview and instructions. |

---

## Usage Instructions

> ⚠️ This lab is intended for educational purposes and should not be run in a production environment without modification.

1. **Set up AWS credentials** (via CLI or environment variables).  
2. **Install dependencies** (for Python scripts):

```bash
pip install -r requirements.txt
