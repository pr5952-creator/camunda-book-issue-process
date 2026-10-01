# camunda-book-issue-process
Camunda 8 BPMN Book Issue Process with Camunda Form
# Camunda 8 – Book Issue Process

## Process
This project models a simple Book Issue Request process using Camunda 8.

### BPMN Flow
Start Event → REQUEST BOOK → End Event

## Form Fields

| Field | Key | Type |
|---|---|---|
| Student Name | studentName | Text |
| Book Name | bookName | Text |
| Issue Date | issueDate | Date |

## Camunda Configuration

- Process Name: Book Issue Process
- User Task: REQUEST BOOK
- Form ID: bookIssueForm
- Executable: Yes
- Runtime: Camunda 8.9

## Files

- `Book-Issue-Process.bpmn` – BPMN process model
- `bookIssueForm.form` – Camunda Form definition

## Execution

The process was deployed and tested using Camunda 8 Run locally.
