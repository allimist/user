# user
Javascript class for user functions (signup login) for mysql database


mysql table

CREATE TABLE `user` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `type` int(1) DEFAULT NULL,
  `email` varchar(45) NOT NULL,
  `password` varchar(60) NOT NULL,
  `status` int(1) NOT NULL,
  `first_name` varchar(20) DEFAULT NULL,
  `last_name` varchar(20) DEFAULT NULL,
  `phone` varchar(20) DEFAULT NULL,
  `country_code` varchar(2) DEFAULT NULL,
  `state_code` varchar(2) DEFAULT NULL,
  `city` varchar(20) DEFAULT NULL,
  `address` varchar(45) DEFAULT NULL,
  `created` datetime NOT NULL DEFAULT CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=utf8;
