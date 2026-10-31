# 02. User Stories and Tasks
## OPA Portal Redevelopment

This document describes user requirements for the OPA Portal
redevelopment using Agile user stories.

The stories represent the needs of staff members and administrative
users who interact with the portal. They provide a basis for
identifying development tasks and acceptance criteria.

---

## User Story 1: Staff Dashboard

**User Story ID:** User 1  

**As a** CPUT staff member,  
**I want** to access a dashboard containing useful information and
recent activities,  
**So that** I can understand my account activity and access relevant
portal functions easily.

### Acceptance Criteria

- The dashboard is accessible to an authenticated user.
- Dashboard information is displayed in a structured layout.
- Recent activities are presented clearly.
- Relevant dashboard widgets display their information correctly.
- The dashboard layout is usable on supported screen sizes.

### Task Breakdown

- Task.1: Review the existing dashboard structure.
- Task.2: Identify dashboard information and widget requirements.
- Task.3: Improve the dashboard layout and presentation.
- Task.4: Implement or update the recent activities widget.
- Task.5: Test dashboard functionality and display.

---

## User Story 2: Unified Service Requests

**User Story ID:** User 2  

**As a** staff member,  
**I want** to access a centralised request process for available
services,  
**So that** I can submit and monitor the services I need without
navigating separate request processes.

### Acceptance Criteria

- Available request types are presented clearly.
- Staff can identify the service they want to request.
- Request information is captured through the relevant form.
- Submitted requests are stored and associated with the relevant user.
- Request information can be accessed by authorised administrators.

### Task Breakdown

- Task.1: Review the existing request models and workflow.
- Task.2: Identify the available request categories.
- Task.3: Structure the unified Requests interface.
- Task.4: Review request forms and validation.
- Task.5: Test request submission and retrieval.

---

## User Story 3: VPN Access Requests

**User Story ID:** User 3  

**As a** staff member,  
**I want** to submit a VPN access request,  
**So that** I can request access to the relevant institutional
resources when required.

### Acceptance Criteria

- The staff member can access the VPN request option.
- Required request information is captured.
- The request is stored against the correct staff member.
- The request can be reviewed by an authorised administrator.
- Request status is communicated to the relevant user.
- Approved and rejected requests are handled according to the
  applicable business rules.

### Task Breakdown

- Task.1: Review VPN request requirements.
- Task.2: Review the VPN request submission process.
- Task.3: Implement or maintain request validation.
- Task.4: Review approval and rejection handling.
- Task.5: Test the VPN request lifecycle.

---

## User Story 4: Printing Credit Requests

**User Story ID:** User 4  

**As a** staff member,  
**I want** to submit a printing credit request,  
**So that** I can request printing credits through the OPA Portal.

### Acceptance Criteria

- The printing credit request option is available.
- Required information is validated.
- The request is associated with the correct staff member.
- Authorised administrators can review the request.
- The request status can be communicated to the user.

### Task Breakdown

- Task.1: Review printing credit request requirements.
- Task.2: Review the request form and relevant fields.
- Task.3: Review request storage and relationships.
- Task.4: Review administrative approval functionality.
- Task.5: Test request submission and status changes.

---

## User Story 5: SMS Credit Requests

**User Story ID:** User 5  

**As a** staff member,  
**I want** to request SMS credits through the portal,  
**So that** I can access the relevant institutional service.

### Acceptance Criteria

- The SMS credit request option is accessible.
- Required information is captured and validated.
- Requests are associated with the correct user.
- Authorised administrators can access submitted requests.
- The user can receive relevant request status information.

### Task Breakdown

- Task1: Review SMS credit request requirements.
- Task.2: Review the request submission interface.
- Task.3: Review request validation and database storage.
- Task.4: Review administrative request handling.
- Task.5: Test the SMS request workflow.

---

## User Story 6: Request Approvals

**User Story ID:** User 6  

**As an** authorised approver,  
**I want** to review and approve or reject submitted requests,  
**So that** staff service requests can be processed through an
appropriate administrative workflow.

### Acceptance Criteria

- Authorised approvers can access relevant requests.
- Request information is available for review.
- Approval and rejection actions are handled appropriately.
- Request status is updated correctly.
- The outcome is communicated to the relevant staff member.

### Task Breakdown

- Task.1: Review approval requirements and user permissions.
- Task.2: Review the administrative request interface.
- Task.3: Review approval and rejection actions.
- Task.4: Review request status updates.
- Task.5: Test the approval workflow.

---

## User Story 7: Request Notifications

**User Story ID:** User 7  

**As a** staff member,  
**I want** to receive notifications when my request status changes,  
**So that** I can remain informed about the progress and outcome
of my submission.

### Acceptance Criteria

- Relevant request status changes trigger the appropriate notification.
- The notification is associated with the correct user.
- Database notifications are handled correctly.
- Email notifications are handled according to the notification
  configuration.
- Notification information is accurate and understandable.

### Task Breakdown

- Task.1: Review the existing notification implementation.
- Task.2: Review notification triggers in request workflows.
- Task.3: Review database notification delivery.
- Task.4: Review email notification delivery.
- Task.5: Test notification behaviour for relevant request outcomes.

---

## Reflection

Writing user stories helps translate technical development requirements
into functionality that has value to the people using the system.

The OPA project includes different user roles, including staff members
and administrators. Their requirements are not identical. Staff need
accessible service request processes, while administrators need
appropriate tools to review and manage those requests.

Defining acceptance criteria also provides a clearer way to evaluate
whether a requirement has been implemented correctly. The stories
can be refined as the project requirements and development priorities
become clearer.
