# CadatroAPI
Cadastro de Funcionario

CREATE TABLE `departamento` (
	`Dietor` CHAR(25) NULL DEFAULT NULL,
	`Gerente` CHAR(25) NULL DEFAULT NULL,
	`Supervisdor` CHAR(25) NULL DEFAULT NULL,
	`Funcionario de Limpeza` CHAR(25) NULL DEFAULT NULL,
	`Funcionario de Manuntecao` CHAR(25) NULL DEFAULT NULL,
	`Funcionario Almoxarifado` CHAR(25) NULL DEFAULT NULL
)
COLLATE='utf8mb4_0900_ai_ci'
ENGINE=InnoDB
;
