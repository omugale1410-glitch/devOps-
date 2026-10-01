# 6. Functional Requirements Specification (FRS)

Functional requirements define the operations the proposed system is expected to support.

## 6.1 Main Workflows

**Student:** registration → profile creation → verification → authorized record access

**Faculty:** login → choose course/class → record attendance → save → review

**Examination staff:** login → enter/update marks → verify → publish according to permission

**Administrator:** search student → inspect/update authorized record → generate report

## 6.2 Requirements

| ID | Module | Requirement |
| --- | --- | --- |
| FR-01 | Authentication | The system shall authenticate authorized users. |
| FR-02 | Authorization | The system shall enforce permissions based on user role. |
| FR-03 | Registration | The system shall create student records using required fields. |
| FR-04 | Student Records | Authorized users shall be able to view and update permitted records. |
| FR-05 | Course Information | The system shall maintain relevant course/academic information. |
| FR-06 | Attendance | Faculty shall be able to record attendance for assigned classes. |
| FR-07 | Attendance View | Students and authorized staff shall be able to view permitted attendance information. |
| FR-08 | Examination Results | Authorized examination staff shall be able to enter and update result information. |
| FR-09 | Verification | Result information shall support an authorization/verification step. |
| FR-10 | Reporting | Authorized users shall be able to generate academic reports. |
| FR-11 | Search | Authorized users shall be able to locate relevant student records. |
| FR-12 | Auditability | Important record operations should be traceable for administrative control. |

## 6.3 Functional Priority

The registration, record-management, attendance and reporting capabilities form the initial release. Examination and result functionality is part of the broader platform and can be implemented alongside or after the core MVP workflows.
