# bd-atv06-miguel

CREATE DATABASE bd_festa;
	USE bd_festa;

	CREATE TABLE convidados (
	nome VARCHAR(50),
    idade INT,
    endereco VARCHAR(50)
);
	CREATE TABLE comidas (
	bebida VARCHAR(30),
    salgado VARCHAR(30),
    enfeites VARCHAR(50)
);
    CREATE TABLE organizadores (
	nome VARCHAR(100),
    gastos FLOAT
);

	INSERT INTO convidados (nome,idade,endereco) VALUES
    ('CLAUDIO','18','RUA JOAQUIM 189'),
	('MARIA','21','RUA CASTRO 141'),
	('JOAO','27','RUA MANESTRO 207');
    
	SELECT * FROM convidados;
    
    INSERT INTO comidas (bebida,salgado,enfeites) VALUES
    ('REFRIGERANTE','PIZZA','BALOES'),
	('WHISKY','COXINHAS','FOGOS DE ARTIFICIO'),
	('ENERGETICO','SALGADINHOS','CONFETES');
    
    ALTER TABLE convidados
    ADD id_convidado INT PRIMARY KEY AUTO_INCREMENT;
    
     ALTER TABLE comidas
    ADD id_comidas INT PRIMARY KEY AUTO_INCREMENT;
    
     ALTER TABLE organizadores
    ADD id_organizadores INT PRIMARY KEY AUTO_INCREMENT;
    
    SELECT * FROM organizadores;
	DECR https://app.diagrams.net/
