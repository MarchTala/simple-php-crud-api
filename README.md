# Simple PHP CRUD

The Simple PHP CRUD was created to generate API and implement CRUD operations in mobile and web applications.

## Project Description File Structure:

### PHP Files in this project:

1. DBConfig.php
2. InsertStudentData.php
3. ShowAllStudentsList.php
4. UpdateStudentRecord.php
5. DeleteStudentRecord.php

### CRUD Operations From MySQL DB:

1. Create a fresh MySQL database in your online hosting server.
2. Create a Table named as StudentDetailsTable with 5 columns.

```
CREATE TABLE `studentdetailstable` (
  `student_id` int(11) NOT NULL AUTO_INCREMENT,
  `student_name` varchar(255) DEFAULT NULL,
  `student_class` varchar(255) DEFAULT NULL,
  `student_phone_number` varchar(255) DEFAULT NULL,
  `student_email` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`student_id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
```

### PHP Files in this project:

1. DBConfig.php
2. InsertStudentData.php
3. ShowAllStudentsList.php
4. UpdateStudentRecord.php
5. DeleteStudentRecord.php
