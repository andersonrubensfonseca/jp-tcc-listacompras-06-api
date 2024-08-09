-- Criação da tabela lista_compras
CREATE TABLE lista_compras (
    ID INT PRIMARY KEY,
    categoria VARCHAR(100) not null,
    produto varchar(100) not null,
    lista varchar(50),
   quantidade varchar(120) not null
);

-- Criação da Tabela lista_compras
CREATE TABLE lista_compras (
    ID INT PRIMARY KEY,
    Nome VARCHAR(100) NOT NULL,
    Preço DECIMAL(10, 2) NOT NULL
);

-- Criação da Tabela categoria
CREATE TABLE categoria (
    ID INT PRIMARY KEY,
    nome varchar(50)    
);

-- Criação da Tabela produto
CREATE TABLE produto (
    ID INT PRIMARY KEY,
    categoria_id int,
    Nome varchar(50)
  
);
-- Criação da Tabela lista
CREATE TABLE lista (
    ID INT PRIMARY KEY,
    Nome varchar(50),
    data varchar(20)
);
-- cricão da tabela lista_produtos
CREATE TABLE lista_produto (
   ID INT PRIMARY KEY,
	produtos_id int,
    lista_id int,
    quantidade_id int
);







