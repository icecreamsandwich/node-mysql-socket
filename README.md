# Real time app using socket.io
### Developing basic app to allow user to add comments and everyone else can see it on real time.

- Download the code. 
     git clone https://github.com/icecreamsandwich/node-mysql-socket.git
     
- Run `npm install` to install dependencies.

- Create the database and table in mysql 

create database `fbstatus`
--
-- Table structure for table `status`
--

CREATE TABLE IF NOT EXISTS `status` (
  `status_id` int(30) NOT NULL AUTO_INCREMENT,
  `s_text` text NOT NULL,
  `t_status` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
  PRIMARY KEY (`status_id`)
) ENGINE=InnoDB  DEFAULT CHARSET=latin1 AUTO_INCREMENT=53 ;
    
- Visit `localhost:3000` to view the app.
