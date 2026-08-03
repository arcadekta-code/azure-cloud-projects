# Troubleshooting Guide

## Issue 1 - IIS Installation Took Longer Than Expected

**Problem**

The IIS installation remained on the installation progress screen for several minutes.

**Resolution**

Waited for the installation to complete successfully without interrupting the process.

---

## Issue 2 - Website Not Accessible

**Problem**

Website was not accessible initially.

**Resolution**

Verified IIS installation, checked the Public IP, and confirmed that the HTTP (Port 80) rule was allowed in the Network Security Group (NSG).

---

## Issue 3 - Scheduled Shutdown Configuration

**Problem**

The preferred scheduled shutdown time was not accepted.

**Resolution**

Configured an available shutdown time and later used **Stop (Deallocated)** to prevent compute charges.

---

## Issue 4 - Cost Optimization

**Problem**

Avoid unnecessary Azure charges after completing the project.

**Resolution**

Stopped (Deallocated) the Virtual Machine and deleted the Resource Group after taking all required screenshots.
