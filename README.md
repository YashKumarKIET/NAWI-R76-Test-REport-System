# NAWI R-76 Test Report System

## 📌 Project Overview

The NAWI R-76 Test Report System is a software application designed to
digitize and automate the testing and test-report generation process
for Non-Automatic Weighing Instruments (NAWI) according to OIML
Recommendation R-76.

The system helps laboratories/inspectors enter instrument details,
record test observations, perform automatic calculations, determine
compliance, and generate standardized test reports.

---

## 🎯 Problem Statement

Development of a Software Program/Application for Generation of Test
Reports for Non-Automatic Weighing Instruments (NAWI) as per OIML
Recommendation R-76.

The application should support:

- Manufacturer and instrument details
- Technical parameter entry
- OIML R-76 compliance determination
- Test observation entry
- Automatic calculations
- Automatic validation
- Standardized test report generation
- Laboratory and instrument detail auto-population
- Photograph and document attachments
- Digital signatures (optional)
- PDF and editable report export
- Test report dashboard and history

---

## 💡 Proposed Solution

Our system provides a centralized digital platform that converts the
NAWI testing process from manual documentation into a structured
digital workflow.

### Workflow

User
↓
Instrument Registration
↓
Input Validation
↓
R-76 Based Test Plan
↓
Test Observation Entry
↓
Automatic Calculation
↓
Compliance Check
↓
PASS / FAIL
↓
Test Report Generation
↓
PDF / Editable Report
↓
Report History & Dashboard

---

## 🚀 Key Features

### 1. Instrument Management
- Manufacturer details
- Model information
- Serial number
- Accuracy class
- Maximum capacity (Max)
- Minimum capacity (Min)
- Verification scale interval (e)
- Actual scale interval (d)
- Other technical parameters

### 2. R-76 Compliance Engine
- Automatic validation of instrument parameters
- Automatic calculations
- Maximum Permissible Error (MPE) determination
- PASS / FAIL determination
- Rule-based compliance checking

### 3. Test Management
The system will support applicable OIML R-76 tests such as:

- Weighing Performance
- Repeatability
- Eccentricity
- Discrimination
- Zero Return
- Creep
- Temperature-related tests
- Voltage variation
- Other applicable tests

### 4. AI / OCR
AI-assisted extraction of instrument information from uploaded
documents or images.

AI will assist with data extraction, while final compliance
determination will be performed using the R-76 rule engine.

### 5. Report Generation
- Automatic report generation
- Standardized report format
- PDF export
- Editable format export
- Test result summary

### 6. Document Management
- Instrument photographs
- Certificates
- Technical documents
- Supporting documents

### 7. Dashboard
- Total reports
- Completed reports
- In-process reports
- Failed reports
- Report history
- Search and filtering

### 8. Audit Trail
- User activity
- Report changes
- Test result changes
- Timestamps

---

## 🏗️ System Architecture

Frontend
    ↓
Backend API
    ↓
R-76 Rule Engine
    ↓
Database
    ↓
Report Generation

AI/OCR
    ↓
Data Extraction
    ↓
Human Verification
    ↓
R-76 Rule Engine

---

## 🛠️ Technology Stack

### Frontend
- React.js
- Tailwind CSS

### Backend
- Python
- FastAPI

### Database
- PostgreSQL

### AI
- OCR / AI-based document extraction

### Version Control
- Git
- GitHub

### Testing / Demo
- Ngrok

---

## 📁 Project Structure

```text
NAWI-R76-Test-Report-System/
│
├── frontend/
│
├── backend/
│
├── ai/
│
├── database/
│
├── reports/
│
├── docs/
│
├── README.md
│
└── .gitignore
