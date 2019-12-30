In this project, I tried to create a basic student management system with Java Swing.
As database I used Mysql with Jdbc. 
I'll continue to update and add the project periodically. 
I have added a button named "Go" to pass the login process.
Mysql information; 
username : localhost
password : 12345
Mysql statements; 
CREATE TABLE `admin` (
  `adminId` int(195) NOT NULL AUTO_INCREMENT,
  `adminMail` varchar(96) DEFAULT NULL,
  `adminName` varchar(97) DEFAULT NULL,
  `adminPassword` varchar(95) DEFAULT NULL,
  PRIMARY KEY (`adminId`)
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

INSERT INTO `studentproject`.`admin` (`adminId`, `adminMail`, `adminName`, `adminPassword`) VALUES ('01', 'admin@gmail.com', 'admin', '12345');

CREATE TABLE `student` (
  `studentId` int(22) NOT NULL AUTO_INCREMENT,
  `studentName` varchar(105) DEFAULT NULL,
  `studentParentName` varchar(105) DEFAULT NULL,
  `studentPhone` int(40) DEFAULT NULL,
  `studentAddress` varchar(125) DEFAULT NULL,
  `studentClass` int(11) DEFAULT NULL,
  PRIMARY KEY (`studentId`)
) ENGINE=InnoDB AUTO_INCREMENT=6 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

INSERT INTO `studentproject`.`student`
(`studentId`,
`studentName`,
`studentParentName`,
`studentPhone`,
`studentAddress`,
`studentClass`)
VALUES
(<{studentId: }>,
<{studentName: }>,
<{studentParentName: }>,
<{studentPhone: }>,
<{studentAddress: }>,
<{studentClass: }>);

