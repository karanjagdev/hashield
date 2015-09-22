- Error log by karan

//---------Added DATABASE , Version of herc : 14389

CREATE TABLE IF NOT EXISTS `global_reg_value` (
  `char_id` int(11) unsigned NOT NULL default '0',
  `str` varchar(255) NOT NULL default '',
  `value` varchar(255) NOT NULL default '0',
  `type` tinyint(1) NOT NULL default '3',
  `account_id` int(11) unsigned NOT NULL default '0',
  PRIMARY KEY  (`char_id`,`str`,`account_id`),
  KEY `account_id` (`account_id`),
  KEY `char_id` (`char_id`)
) ENGINE=MyISAM;

//-------------------

Interreg :  INSERT INTO `interreg` (`varname`, `value`) VALUES
('unique_id', '0');

SQL error will not let harmony char server connect