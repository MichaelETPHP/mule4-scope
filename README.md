# mule4-scope
Async Scope is an asynchronous processing block that executes simultaneously with the main flow.


CREATE TABLE `tb_product` (
	`id` INT(11) NOT NULL AUTO_INCREMENT,
	`product_name` VARCHAR(50) NULL DEFAULT NULL COLLATE 'latin1_swedish_ci',
	`description` LONGTEXT NULL DEFAULT NULL COLLATE 'latin1_swedish_ci',
	`video_url` LONGTEXT NULL DEFAULT NULL COLLATE 'latin1_swedish_ci',
	`category_id` INT(11) NULL DEFAULT NULL,
	`price` FLOAT NULL DEFAULT NULL,
	PRIMARY KEY (`id`) USING BTREE
)
COLLATE='latin1_swedish_ci'
ENGINE=InnoDB
AUTO_INCREMENT=11438
;
