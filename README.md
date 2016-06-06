# Databases

Tabela de usuários

CREATE TABLE `usuario` (
  `id` INT NOT NULL,
  `nome` VARCHAR(100) NULL,
  `perfil` VARCHAR(100) NULL,
  `email` VARCHAR(100) NULL,
  `cpf` VARCHAR(100) NULL,
  `fone` VARCHAR(100) NULL,
  `senha` VARCHAR(100) NULL,
  PRIMARY KEY (`id`),
  INDEX `email_idx` (`email` ASC),
  INDEX `cpf_idx` (`cpf` ASC));
