# Hostel Management System (HMS)

## Business Rules for the DBMS

The Hostel Management System (HMS) incorporates the following business rules:

- **Hostel-Student Relationship**:
  - Each hostel accommodates multiple students, but a student can only reside in one hostel at a time.

- **Hostel-Staff Relationship**:
  - A hostel is staffed by multiple individuals, but each staff member is assigned to only one hostel at a time.

- **Room Allotment**:
  - Each student is allotted one room at a time; multiple room allotments for a single student are not permitted.

- **Room Maintenance**:
  - Rooms are equipped with various maintenance items such as lights, fans, pillows, windows, etc.

- **Visitor Management**:
  - Students may have multiple visitors, but each visitor is associated with only one student.

- **Attendance Tracking**:
  - Students can mark their attendance multiple times a day, with each attendance entry associated with a specific student.

- **Complaint Resolution**:
  - Staff members can address multiple complaints lodged by a single student.

- **Medical Record Management**:
  - Students may have multiple medical records, but each medical record is associated with only one student.

- **Fee Payment**:
  - Each student makes exactly one payment for hostel fees, with each payment associated with only one student.

- **Furniture Allocation**:
  - Students in a room may use multiple pieces of furniture, with each piece of furniture assigned to a specific student within a given room.

- **Leave Application**:
  - Students can request multiple leaves, but each leave application is made by only one student.
