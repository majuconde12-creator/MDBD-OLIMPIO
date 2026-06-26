-- phpMyAdmin SQL Dump
-- version 5.2.1
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Tempo de geração: 26/06/2026 às 14:55
-- Versão do servidor: 10.4.32-MariaDB
-- Versão do PHP: 8.2.12

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Banco de dados: `bd_escola_maria`
--

-- --------------------------------------------------------

--
-- Estrutura para tabela `alunos`
--

CREATE TABLE `alunos` (
  `id_aluno` int(11) NOT NULL,
  `id_dados` int(11) NOT NULL,
  `id_rua` int(11) NOT NULL,
  `data_de_nascimento` date DEFAULT NULL,
  `email` varchar(254) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `alunos`
--

INSERT INTO `alunos` (`id_aluno`, `id_dados`, `id_rua`, `data_de_nascimento`, `email`) VALUES
(1, 21, 1, '2008-04-12', 'enzo.santos08@gmail.com'),
(2, 22, 2, '2009-11-23', 'duda.costa09@gmail.com'),
(3, 23, 3, '2008-07-05', 'joao.pedro.oliveira@gmail.com'),
(4, 24, 4, '2009-02-14', 'anaclara.souza@gmail.com'),
(5, 25, 5, '2008-09-30', 'pedro.lima.henrique@gmail.com'),
(6, 26, 1, '2009-05-18', 'malu.silva2009@gmail.com'),
(7, 27, 2, '2008-01-25', 'luiz.felipe.pereira@gmail.com'),
(8, 28, 3, '2009-08-08', 'anajulia.rod@gmail.com'),
(9, 29, 4, '2008-12-11', 'cadu.alves08@gmail.com'),
(10, 30, 5, '2009-03-22', 'valentina.rib@gmail.com'),
(11, 31, 1, '2008-06-17', 'marcos.carvalho@gmail.com'),
(12, 32, 2, '2009-10-04', 'bia.hellen.gomes@gmail.com'),
(13, 33, 3, '2008-03-14', 'jg.martins08@gmail.com'),
(14, 34, 4, '2009-07-29', 'mari.vitoria.b@gmail.com'),
(15, 35, 5, '2008-10-09', 'paulo.melo.roberto@gmail.com'),
(16, 36, 1, '2009-01-19', 'ana.bia.fernandes@gmail.com'),
(17, 37, 2, '2008-05-24', 'lucas.g.vieira@gmail.com'),
(18, 38, 3, '2009-12-05', 'maria.alice.cardoso@gmail.com'),
(19, 39, 4, '2008-02-28', 'luiz.gustavo.rocha@gmail.com'),
(20, 40, 5, '2009-06-11', 'leticia.teixeira09@gmail.com'),
(21, 41, 1, '2008-08-19', 'vitor.hugo.couto@gmail.com'),
(22, 42, 2, '2009-04-03', 'clara.bia.nunes@gmail.com'),
(23, 43, 3, '2008-11-07', 'matheus.neves08@gmail.com'),
(24, 44, 4, '2009-09-13', 'julia.fernanda.m@gmail.com'),
(25, 45, 5, '2008-07-22', 'davi.lucca.fonseca@gmail.com'),
(26, 46, 1, '2009-02-27', 'yasmin.ramos09@gmail.com'),
(27, 47, 2, '2008-10-15', 'thiago.andre.campos@gmail.com'),
(28, 48, 3, '2009-05-04', 'larissa.m.freitas@gmail.com'),
(29, 49, 4, '2008-04-20', 'samuel.levi.pires@gmail.com'),
(30, 50, 5, '2009-11-12', 'laura.sophia.moraes@gmail.com');

-- --------------------------------------------------------

--
-- Estrutura para tabela `alunos_responsaveis`
--

CREATE TABLE `alunos_responsaveis` (
  `id_aluno` int(11) NOT NULL,
  `id_responsavel` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `alunos_responsaveis`
--

INSERT INTO `alunos_responsaveis` (`id_aluno`, `id_responsavel`) VALUES
(1, 1),
(2, 2),
(3, 3),
(4, 4),
(5, 5),
(6, 6),
(7, 7),
(8, 8),
(9, 9),
(10, 10),
(11, 11),
(12, 12),
(13, 13),
(14, 14),
(15, 15),
(16, 16),
(17, 17),
(18, 18),
(19, 19),
(20, 20),
(21, 21),
(22, 22),
(23, 23),
(24, 24),
(25, 25),
(26, 26),
(27, 27),
(28, 28),
(29, 29),
(30, 30);

-- --------------------------------------------------------

--
-- Estrutura para tabela `avaliacoes`
--

CREATE TABLE `avaliacoes` (
  `id_avaliacao` int(11) NOT NULL,
  `id_disciplina` int(11) NOT NULL,
  `descricao` text DEFAULT NULL,
  `data_avaliacao` date DEFAULT NULL,
  `valor_avaliacao` decimal(5,2) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `avaliacoes`
--

INSERT INTO `avaliacoes` (`id_avaliacao`, `id_disciplina`, `descricao`, `data_avaliacao`, `valor_avaliacao`) VALUES
(1, 1, 'Prova Teórica de Álgebra Relacional', '2026-04-15', 10.00),
(2, 1, 'Trabalho Prático de Modelagem DER', '2026-05-10', 10.00),
(3, 1, 'Laboratório de Queries Avançadas DML', '2026-06-05', 10.00),
(4, 1, 'Projeto de Banco de Dados Integrado', '2026-06-20', 10.00),
(5, 2, 'Avaliação de Pseudocódigo e Fluxogramas', '2026-04-18', 10.00),
(6, 2, 'Desafio de Estruturas Condicionais', '2026-05-14', 10.00),
(7, 2, 'Prova Prática de Laços de Repetição', '2026-06-08', 10.00),
(8, 2, 'Desenvolvimento de Algoritmo Final', '2026-06-22', 10.00),
(9, 11, 'Resenha de Escolas da Administração', '2026-04-12', 10.00),
(10, 11, 'Estudo de Caso sobre Organizações', '2026-05-08', 10.00),
(11, 11, 'Seminário de Planejamento Estratégico', '2026-06-02', 10.00),
(12, 11, 'Prova Bimestral Dissertativa', '2026-06-18', 10.00);

-- --------------------------------------------------------

--
-- Estrutura para tabela `bairros`
--

CREATE TABLE `bairros` (
  `id_bairro` int(11) NOT NULL,
  `id_cidade` int(11) NOT NULL,
  `nome_do_bairro` varchar(100) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `bairros`
--

INSERT INTO `bairros` (`id_bairro`, `id_cidade`, `nome_do_bairro`) VALUES
(1, 1, 'Centro'),
(2, 1, 'Jardim Aquarius'),
(3, 1, 'Vila Industrial'),
(4, 1, 'Jardim Satélite'),
(5, 1, 'Bosque dos Eucaliptos');

-- --------------------------------------------------------

--
-- Estrutura para tabela `boletins`
--

CREATE TABLE `boletins` (
  `id_boletim` int(11) NOT NULL,
  `media_final` decimal(5,2) DEFAULT NULL,
  `situacao` varchar(30) DEFAULT NULL,
  `frequencia` decimal(5,2) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `boletins`
--

INSERT INTO `boletins` (`id_boletim`, `media_final`, `situacao`, `frequencia`) VALUES
(1, 8.50, 'APROVADO', 95.00),
(2, 7.20, 'APROVADO', 88.50),
(3, 6.00, 'RECUPERAÇÃO', 78.00),
(4, 9.00, 'APROVADO', 100.00),
(5, 5.50, 'RECUPERAÇÃO', 82.00),
(6, 4.50, 'REPROVADO', 70.00),
(7, 8.00, 'APROVADO', 94.00),
(8, 7.50, 'APROVADO', 91.00),
(9, 6.80, 'APROVADO', 85.00),
(10, 9.50, 'APROVADO', 98.00),
(11, 8.70, 'APROVADO', 96.00),
(12, 7.10, 'APROVADO', 89.00),
(13, 5.80, 'RECUPERAÇÃO', 80.50),
(14, 9.20, 'APROVADO', 99.00),
(15, 6.40, 'APROVADO', 87.00),
(16, 3.80, 'REPROVADO', 65.00),
(17, 8.30, 'APROVADO', 93.00),
(18, 7.90, 'APROVADO', 92.00),
(19, 6.90, 'APROVADO', 86.00),
(20, 9.70, 'APROVADO', 97.50),
(21, 8.10, 'APROVADO', 95.00),
(22, 7.00, 'APROVADO', 88.00),
(23, 5.90, 'RECUPERAÇÃO', 81.00),
(24, 9.10, 'APROVADO', 100.00),
(25, 6.20, 'APROVADO', 85.50),
(26, 4.00, 'REPROVADO', 68.00),
(27, 8.40, 'APROVADO', 94.50),
(28, 7.60, 'APROVADO', 90.00),
(29, 6.70, 'APROVADO', 84.00),
(30, 9.90, 'APROVADO', 99.00);

-- --------------------------------------------------------

--
-- Estrutura para tabela `boletins_disciplinas`
--

CREATE TABLE `boletins_disciplinas` (
  `id_boletim` int(11) NOT NULL,
  `id_disciplina` int(11) NOT NULL,
  `situacao_disciplina` varchar(30) DEFAULT NULL,
  `nota_aluno` decimal(5,2) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `boletins_disciplinas`
--

INSERT INTO `boletins_disciplinas` (`id_boletim`, `id_disciplina`, `situacao_disciplina`, `nota_aluno`) VALUES
(1, 1, 'APROVADO', 8.50),
(1, 2, 'APROVADO', 9.00),
(2, 11, 'APROVADO', 7.20),
(2, 12, 'APROVADO', 7.50),
(3, 21, 'RECUPERAÇÃO', 6.00),
(3, 22, 'APROVADO', 6.50),
(6, 1, 'REPROVADO', 4.50),
(6, 2, 'RECUPERAÇÃO', 5.00),
(7, 11, 'APROVADO', 8.00),
(7, 12, 'APROVADO', 8.20),
(8, 21, 'APROVADO', 7.50),
(8, 22, 'APROVADO', 7.80),
(11, 1, 'APROVADO', 8.70),
(11, 2, 'APROVADO', 8.50),
(12, 11, 'APROVADO', 7.10),
(12, 12, 'APROVADO', 7.00),
(13, 21, 'RECUPERAÇÃO', 5.80),
(13, 22, 'RECUPERAÇÃO', 5.50),
(16, 1, 'REPROVADO', 3.80),
(16, 2, 'REPROVADO', 4.00),
(17, 11, 'APROVADO', 8.30),
(17, 12, 'APROVADO', 8.50),
(18, 21, 'APROVADO', 7.90),
(18, 22, 'APROVADO', 8.00),
(21, 1, 'APROVADO', 8.10),
(21, 2, 'APROVADO', 8.30),
(22, 11, 'APROVADO', 7.00),
(22, 12, 'APROVADO', 7.20),
(23, 21, 'RECUPERAÇÃO', 5.90),
(23, 22, 'RECUPERAÇÃO', 5.70),
(26, 1, 'REPROVADO', 4.00),
(26, 2, 'REPROVADO', 4.20),
(27, 11, 'APROVADO', 8.40),
(27, 12, 'APROVADO', 8.60),
(28, 21, 'APROVADO', 7.60),
(28, 22, 'APROVADO', 7.50);

-- --------------------------------------------------------

--
-- Estrutura para tabela `cidades`
--

CREATE TABLE `cidades` (
  `id_cidade` int(11) NOT NULL,
  `id_estado` int(11) NOT NULL,
  `nome_da_cidade` varchar(100) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `cidades`
--

INSERT INTO `cidades` (`id_cidade`, `id_estado`, `nome_da_cidade`) VALUES
(1, 1, 'São José dos Campos'),
(2, 2, 'Niterói'),
(3, 3, 'Uberlândia'),
(4, 4, 'Porto Alegre'),
(5, 5, 'Florianópolis');

-- --------------------------------------------------------

--
-- Estrutura para tabela `coordenadores`
--

CREATE TABLE `coordenadores` (
  `id_coordenador` int(11) NOT NULL,
  `id_dados` int(11) NOT NULL,
  `id_rua` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `coordenadores`
--

INSERT INTO `coordenadores` (`id_coordenador`, `id_dados`, `id_rua`) VALUES
(1, 1, 1),
(2, 2, 2),
(3, 3, 3),
(4, 4, 4),
(5, 5, 5);

-- --------------------------------------------------------

--
-- Estrutura para tabela `cursos`
--

CREATE TABLE `cursos` (
  `id_curso` int(11) NOT NULL,
  `nome_do_curso` varchar(100) NOT NULL,
  `carga_horaria` decimal(5,0) DEFAULT NULL,
  `duracao` varchar(50) DEFAULT NULL,
  `descricao` text DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `cursos`
--

INSERT INTO `cursos` (`id_curso`, `nome_do_curso`, `carga_horaria`, `duracao`, `descricao`) VALUES
(1, 'Desenvolvimento de Sistemas', 1200, '18 meses', 'Focado em Engenharia de Software e Banco de Dados.'),
(2, 'Administração', 1000, '12 meses', 'Focado em Gestão Empresarial e Financeira.'),
(3, 'Logística', 800, '12 meses', 'Focado em Cadeia de Suprimentos e Transportes.'),
(4, 'Recursos Humanos', 800, '12 meses', 'Focado em Gestão de Pessoas e Dpto Pessoal.'),
(5, 'Marketing Digital', 900, '12 meses', 'Estratégias de Comunicação e Redes Sociais.');

-- --------------------------------------------------------

--
-- Estrutura para tabela `cursos_disciplinas`
--

CREATE TABLE `cursos_disciplinas` (
  `id_curso` int(11) NOT NULL,
  `id_disciplina` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- --------------------------------------------------------

--
-- Estrutura para tabela `dados_pessoais`
--

CREATE TABLE `dados_pessoais` (
  `id_dados` int(11) NOT NULL,
  `cpf` char(11) NOT NULL,
  `formacao` varchar(100) DEFAULT NULL,
  `email` varchar(254) NOT NULL,
  `numero_da_casa` decimal(6,0) DEFAULT NULL,
  `nome` varchar(150) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `dados_pessoais`
--

INSERT INTO `dados_pessoais` (`id_dados`, `cpf`, `formacao`, `email`, `numero_da_casa`, `nome`) VALUES
(1, '11122233344', 'Doutorado em TI', 'carlos.silva@escola.com', 120, 'Carlos Augusto Silva'),
(2, '22233344455', 'Mestrado em Letras', 'marisa.souza@escola.com', 45, 'Marisa Oliveira Souza'),
(3, '33344455566', 'Doutorado em Administração', 'roberto.santos@escola.com', 782, 'Roberto dos Santos'),
(4, '44455566677', 'Especialização em RH', 'aline.costa@escola.com', 14, 'Aline Costa Lima'),
(5, '55566677788', 'Mestrado em Marketing', 'beatriz.rocha@escola.com', 90, 'Beatriz Lima Rocha'),
(6, '66677788899', 'Mestrado em Redes', 'marcos.antunes@escola.com', 231, 'Marcos Ribeiro Antunes'),
(7, '77788899900', 'Especialização em Logística', 'daniel.neto@escola.com', 56, 'Daniel Mendes Neto'),
(8, '88899900011', 'Doutorado em Matemática', 'priscila.dias@escola.com', 404, 'Priscila Dias'),
(9, '99900011122', 'Especialização em Finanças', 'renato.vieira@escola.com', 19, 'Renato Vieira'),
(10, '00011122233', 'Mestrado em Sistemas', 'sandra.regina@escola.com', 88, 'Sandra Regina'),
(11, '12345678901', 'Especialização em Web', 'juliano.c@escola.com', 302, 'Juliano Carvalho'),
(12, '23456789012', 'Mestrado em Negócios', 'tatiane.castro@escola.com', 74, 'Tatiane Castro'),
(13, '34567890123', 'Especialização em Estoque', 'vitor.prado@escola.com', 510, 'Vitor Hugo Prado'),
(14, '45678901234', 'Mestrado em Psicologia', 'patricia.f@escola.com', 63, 'Patrícia Fagundes'),
(15, '56789012345', 'Doutorado em Comunicação', 'murilo.b@escola.com', 12, 'Murilo Benício'),
(16, '67890123456', 'Mestrado em Big Data', 'fernanda.s@escola.com', 95, 'Fernanda Souza'),
(17, '78901234567', 'Especialização em Processos', 'rodrigo.faro@escola.com', 112, 'Rodrigo Faro'),
(18, '89012345678', 'Mestrado em Comércio', 'camila.p@escola.com', 84, 'Camila Pitanga'),
(19, '90123456789', 'Especialização em Mídias', 'thiago.l@escola.com', 27, 'Thiago Lacerda'),
(20, '01234567890', 'Doutorado em Engenharia', 'giovanna.a@escola.com', 150, 'Giovanna Antonelli'),
(21, '18469273510', 'Ensino Médio Incompleto', 'enzo.santos08@gmail.com', 451, 'Enzo Gabriel Santos'),
(22, '92358147602', 'Ensino Médio Incompleto', 'duda.costa09@gmail.com', 12, 'Maria Eduarda Costa'),
(23, '34197528640', 'Ensino Médio Incompleto', 'joao.pedro.oliveira@gmail.com', 88, 'João Pedro Oliveira'),
(24, '75621493805', 'Ensino Médio Incompleto', 'anaclara.souza@gmail.com', 54, 'Ana Clara Souza'),
(25, '49218375601', 'Ensino Médio Incompleto', 'pedro.lima.henrique@gmail.com', 102, 'Pedro Henrique Lima'),
(26, '61584932704', 'Ensino Médio Incompleto', 'malu.silva2009@gmail.com', 67, 'Maria Luiza Silva'),
(27, '23876149503', 'Ensino Médio Incompleto', 'luiz.felipe.pereira@gmail.com', 9, 'Luiz Felipe Pereira'),
(28, '80492317650', 'Ensino Médio Incompleto', 'anajulia.rod@gmail.com', 34, 'Ana Julia Rodrigues'),
(29, '57138469208', 'Ensino Médio Incompleto', 'cadu.alves08@gmail.com', 115, 'Carlos Eduardo Alves'),
(30, '19248573602', 'Ensino Médio Incompleto', 'valentina.rib@gmail.com', 76, 'Maria Valentina Ribeiro'),
(31, '84391527604', 'Ensino Médio Incompleto', 'marcos.carvalho@gmail.com', 23, 'Antônio Marcos Carvalho'),
(32, '36251497801', 'Ensino Médio Incompleto', 'bia.hellen.gomes@gmail.com', 801, 'Beatriz Hellen Gomes'),
(33, '90518342706', 'Ensino Médio Incompleto', 'jg.martins08@gmail.com', 44, 'João Gabriel Martins'),
(34, '47169253802', 'Ensino Médio Incompleto', 'mari.vitoria.b@gmail.com', 190, 'Mariana Vitória Barbosa'),
(35, '62839417509', 'Ensino Médio Incompleto', 'paulo.melo.roberto@gmail.com', 32, 'Paulo Roberto Melo'),
(36, '13975286407', 'Ensino Médio Incompleto', 'ana.bia.fernandes@gmail.com', 50, 'Ana Beatriz Fernandes'),
(37, '58421697301', 'Ensino Médio Incompleto', 'lucas.g.vieira@gmail.com', 612, 'Lucas Gabriel Vieira'),
(38, '29517364805', 'Ensino Médio Incompleto', 'maria.alice.cardoso@gmail.com', 70, 'Maria Alice Cardoso'),
(39, '73648219502', 'Ensino Médio Incompleto', 'luiz.gustavo.rocha@gmail.com', 93, 'Luiz Gustavo Rocha'),
(40, '41295738604', 'Ensino Médio Incompleto', 'leticia.teixeira09@gmail.com', 5, 'Letícia Maria Teixeira'),
(41, '95834127608', 'Ensino Médio Incompleto', 'vitor.hugo.couto@gmail.com', 124, 'Vitor Hugo Couto'),
(42, '60471953207', 'Ensino Médio Incompleto', 'clara.bia.nunes@gmail.com', 68, 'Clara Beatriz Nunes'),
(43, '31985247601', 'Ensino Médio Incompleto', 'matheus.neves08@gmail.com', 31, 'Matheus Henrique Neves'),
(44, '84216953704', 'Ensino Médio Incompleto', 'julia.fernanda.m@gmail.com', 205, 'Julia Fernanda Mendes'),
(45, '52736149806', 'Ensino Médio Incompleto', 'davi.lucca.fonseca@gmail.com', 99, 'Davi Lucca Fonseca'),
(46, '16954283702', 'Ensino Médio Incompleto', 'yasmin.ramos09@gmail.com', 73, 'Yasmin Vitória Ramos'),
(47, '73825196405', 'Ensino Médio Incompleto', 'thiago.andre.campos@gmail.com', 142, 'Thiago André Campos'),
(48, '48139527609', 'Ensino Médio Incompleto', 'larissa.m.freitas@gmail.com', 81, 'Larissa Manoela Freitas'),
(49, '92541638701', 'Ensino Médio Incompleto', 'samuel.levi.pires@gmail.com', 52, 'Samuel Levi Pires'),
(50, '61394827504', 'Ensino Médio Incompleto', 'laura.sophia.moraes@gmail.com', 307, 'Laura Sophia Moraes');

-- --------------------------------------------------------

--
-- Estrutura para tabela `disciplinas`
--

CREATE TABLE `disciplinas` (
  `id_disciplina` int(11) NOT NULL,
  `id_curso` int(11) NOT NULL,
  `id_professor` int(11) NOT NULL,
  `carga_horaria` decimal(5,0) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `disciplinas`
--

INSERT INTO `disciplinas` (`id_disciplina`, `id_curso`, `id_professor`, `carga_horaria`) VALUES
(1, 1, 1, 80),
(2, 1, 2, 80),
(3, 1, 3, 60),
(4, 1, 4, 60),
(5, 1, 5, 40),
(6, 1, 6, 40),
(7, 1, 7, 60),
(8, 1, 8, 40),
(9, 1, 9, 60),
(10, 1, 10, 40),
(11, 2, 11, 80),
(12, 2, 12, 60),
(13, 2, 13, 60),
(14, 2, 14, 40),
(15, 2, 15, 40),
(16, 2, 16, 60),
(17, 2, 17, 40),
(18, 2, 18, 60),
(19, 2, 19, 40),
(20, 2, 20, 40),
(21, 3, 1, 80),
(22, 3, 2, 60),
(23, 3, 3, 60),
(24, 3, 4, 40),
(25, 3, 5, 40),
(26, 3, 6, 60),
(27, 3, 7, 40),
(28, 3, 8, 60),
(29, 3, 9, 40),
(30, 3, 10, 40),
(31, 4, 11, 80),
(32, 4, 12, 60),
(33, 4, 13, 60),
(34, 4, 14, 40),
(35, 4, 15, 40),
(36, 4, 16, 60),
(37, 4, 17, 40),
(38, 4, 18, 60),
(39, 4, 19, 40),
(40, 4, 20, 40),
(41, 5, 1, 80),
(42, 5, 2, 60),
(43, 5, 3, 60),
(44, 5, 4, 40),
(45, 5, 5, 40),
(46, 5, 6, 60),
(47, 5, 7, 40),
(48, 5, 8, 60),
(49, 5, 9, 40),
(50, 5, 10, 40);

-- --------------------------------------------------------

--
-- Estrutura para tabela `estados`
--

CREATE TABLE `estados` (
  `id_estado` int(11) NOT NULL,
  `nome_do_estado` varchar(50) NOT NULL,
  `sigla` char(2) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `estados`
--

INSERT INTO `estados` (`id_estado`, `nome_do_estado`, `sigla`) VALUES
(1, 'São Paulo', 'SP'),
(2, 'Rio de Janeiro', 'RJ'),
(3, 'Minas Gerais', 'MG'),
(4, 'Bahia', 'BA'),
(5, 'Paraná', 'PR');

-- --------------------------------------------------------

--
-- Estrutura para tabela `matriculas`
--

CREATE TABLE `matriculas` (
  `id_matricula` int(11) NOT NULL,
  `id_aluno` int(11) NOT NULL,
  `id_turma` int(11) NOT NULL,
  `data_matricula` date DEFAULT NULL,
  `situacao_matricula` varchar(50) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `matriculas`
--

INSERT INTO `matriculas` (`id_matricula`, `id_aluno`, `id_turma`, `data_matricula`, `situacao_matricula`) VALUES
(1, 1, 1, '2026-01-15', 'ATIVA'),
(2, 2, 2, '2026-01-15', 'ATIVA'),
(3, 3, 3, '2026-01-15', 'ATIVA'),
(4, 4, 4, '2026-01-15', 'ATIVA'),
(5, 5, 5, '2026-01-15', 'ATIVA'),
(6, 6, 1, '2026-01-16', 'ATIVA'),
(7, 7, 2, '2026-01-16', 'ATIVA'),
(8, 8, 3, '2026-01-16', 'ATIVA'),
(9, 9, 4, '2026-01-16', 'ATIVA'),
(10, 10, 5, '2026-01-16', 'ATIVA'),
(11, 11, 1, '2026-01-17', 'ATIVA'),
(12, 12, 2, '2026-01-17', 'ATIVA'),
(13, 13, 3, '2026-01-17', 'ATIVA'),
(14, 14, 4, '2026-01-17', 'ATIVA'),
(15, 15, 5, '2026-01-17', 'ATIVA'),
(16, 16, 1, '2026-01-18', 'ATIVA'),
(17, 17, 2, '2026-01-18', 'ATIVA'),
(18, 18, 3, '2026-01-18', 'ATIVA'),
(19, 19, 4, '2026-01-18', 'ATIVA'),
(20, 20, 5, '2026-01-18', 'ATIVA'),
(21, 21, 1, '2026-01-19', 'ATIVA'),
(22, 22, 2, '2026-01-19', 'ATIVA'),
(23, 23, 3, '2026-01-19', 'ATIVA'),
(24, 24, 4, '2026-01-19', 'ATIVA'),
(25, 25, 5, '2026-01-19', 'ATIVA'),
(26, 26, 1, '2026-01-20', 'ATIVA'),
(27, 27, 2, '2026-01-20', 'ATIVA'),
(28, 28, 3, '2026-01-20', 'ATIVA'),
(29, 29, 4, '2026-01-20', 'ATIVA'),
(30, 30, 5, '2026-01-20', 'ATIVA');

-- --------------------------------------------------------

--
-- Estrutura para tabela `matricula_curso`
--

CREATE TABLE `matricula_curso` (
  `id_matricula` int(11) NOT NULL,
  `id_curso` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `matricula_curso`
--

INSERT INTO `matricula_curso` (`id_matricula`, `id_curso`) VALUES
(1, 1),
(2, 2),
(3, 3),
(4, 4),
(5, 5),
(6, 1),
(7, 2),
(8, 3),
(9, 4),
(10, 5),
(11, 1),
(12, 2),
(13, 3),
(14, 4),
(15, 5),
(16, 1),
(17, 2),
(18, 3),
(19, 4),
(20, 5),
(21, 1),
(22, 2),
(23, 3),
(24, 4),
(25, 5),
(26, 1),
(27, 2),
(28, 3),
(29, 4),
(30, 5);

-- --------------------------------------------------------

--
-- Estrutura para tabela `professores`
--

CREATE TABLE `professores` (
  `id_professor` int(11) NOT NULL,
  `id_dados` int(11) NOT NULL,
  `id_rua` int(11) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `professores`
--

INSERT INTO `professores` (`id_professor`, `id_dados`, `id_rua`) VALUES
(1, 1, 1),
(2, 2, 2),
(3, 3, 3),
(4, 4, 4),
(5, 5, 5),
(6, 6, 1),
(7, 7, 2),
(8, 8, 3),
(9, 9, 4),
(10, 10, 5),
(11, 11, 1),
(12, 12, 2),
(13, 13, 3),
(14, 14, 4),
(15, 15, 5),
(16, 16, 1),
(17, 17, 2),
(18, 18, 3),
(19, 19, 4),
(20, 20, 5);

-- --------------------------------------------------------

--
-- Estrutura para tabela `responsaveis`
--

CREATE TABLE `responsaveis` (
  `id_responsavel` int(11) NOT NULL,
  `id_dados` int(11) NOT NULL,
  `id_rua` int(11) NOT NULL,
  `parentesco` varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `responsaveis`
--

INSERT INTO `responsaveis` (`id_responsavel`, `id_dados`, `id_rua`, `parentesco`) VALUES
(1, 51, 1, 'Pai'),
(2, 52, 2, 'Mãe'),
(3, 53, 3, 'Pai'),
(4, 54, 4, 'Mãe'),
(5, 55, 5, 'Pai'),
(6, 56, 1, 'Pai'),
(7, 57, 2, 'Mãe'),
(8, 58, 3, 'Pai'),
(9, 59, 4, 'Mãe'),
(10, 60, 5, 'Mãe'),
(11, 61, 1, 'Pai'),
(12, 62, 2, 'Mãe'),
(13, 63, 3, 'Pai'),
(14, 64, 4, 'Mãe'),
(15, 65, 5, 'Pai'),
(16, 66, 1, 'Mãe'),
(17, 67, 2, 'Pai'),
(18, 68, 3, 'Mãe'),
(19, 69, 4, 'Pai'),
(20, 70, 5, 'Mãe'),
(21, 71, 1, 'Pai'),
(22, 72, 2, 'Mãe'),
(23, 73, 3, 'Pai'),
(24, 74, 4, 'Mãe'),
(25, 75, 5, 'Pai'),
(26, 76, 1, 'Mãe'),
(27, 77, 2, 'Pai'),
(28, 78, 3, 'Mãe'),
(29, 79, 4, 'Pai'),
(30, 80, 5, 'Mãe');

-- --------------------------------------------------------

--
-- Estrutura para tabela `ruas`
--

CREATE TABLE `ruas` (
  `id_rua` int(11) NOT NULL,
  `id_bairro` int(11) NOT NULL,
  `nome_da_rua` varchar(100) NOT NULL,
  `cep` char(8) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `ruas`
--

INSERT INTO `ruas` (`id_rua`, `id_bairro`, `nome_da_rua`, `cep`) VALUES
(1, 1, 'Avenida Nelson dAvila', '12245030'),
(2, 2, 'Rua Alfredo do Nascimento', '12246020'),
(3, 3, 'Rua das Palmeiras', '12220000'),
(4, 4, 'Avenida Andrômeda', '12230000'),
(5, 5, 'Avenida Ouro Fino', '12233000');

-- --------------------------------------------------------

--
-- Estrutura para tabela `telefones`
--

CREATE TABLE `telefones` (
  `id_telefone` int(11) NOT NULL,
  `id_dados` int(11) NOT NULL,
  `numero_tel` varchar(20) DEFAULT NULL,
  `tipo` varchar(20) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `telefones`
--

INSERT INTO `telefones` (`id_telefone`, `id_dados`, `numero_tel`, `tipo`) VALUES
(1, 1, '12988887701', 'Celular Trabalho'),
(2, 2, '12988887702', 'Celular Pessoal'),
(3, 3, '1239215501', 'Fixo Residencial'),
(4, 4, '12988887704', 'Celular'),
(5, 5, '12988887705', 'Celular'),
(6, 21, '12991234501', 'Celular Aluno'),
(7, 22, '12991234502', 'Celular Aluno'),
(8, 51, '12981546601', 'Celular Responsável'),
(9, 52, '12981546602', 'Celular Responsável');

-- --------------------------------------------------------

--
-- Estrutura para tabela `turmas`
--

CREATE TABLE `turmas` (
  `id_turma` int(11) NOT NULL,
  `id_curso` int(11) NOT NULL,
  `ano_letivo` varchar(10) DEFAULT NULL,
  `turno` varchar(20) DEFAULT NULL,
  `sala` varchar(20) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Despejando dados para a tabela `turmas`
--

INSERT INTO `turmas` (`id_turma`, `id_curso`, `ano_letivo`, `turno`, `sala`) VALUES
(1, 1, '2026', 'Manhã', 'Lab TI 1'),
(2, 2, '2026', 'Tarde', 'Sala 201'),
(3, 3, '2026', 'Noite', 'Lab Redes'),
(4, 4, '2026', 'Manhã', 'Sala 105'),
(5, 5, '2026', 'Noite', 'Auditório');

--
-- Índices para tabelas despejadas
--

--
-- Índices de tabela `alunos`
--
ALTER TABLE `alunos`
  ADD PRIMARY KEY (`id_aluno`),
  ADD KEY `id_dados` (`id_dados`),
  ADD KEY `id_rua` (`id_rua`);

--
-- Índices de tabela `alunos_responsaveis`
--
ALTER TABLE `alunos_responsaveis`
  ADD PRIMARY KEY (`id_aluno`,`id_responsavel`),
  ADD KEY `id_responsavel` (`id_responsavel`);

--
-- Índices de tabela `avaliacoes`
--
ALTER TABLE `avaliacoes`
  ADD PRIMARY KEY (`id_avaliacao`),
  ADD KEY `id_disciplina` (`id_disciplina`);

--
-- Índices de tabela `bairros`
--
ALTER TABLE `bairros`
  ADD PRIMARY KEY (`id_bairro`),
  ADD KEY `id_cidade` (`id_cidade`);

--
-- Índices de tabela `boletins`
--
ALTER TABLE `boletins`
  ADD PRIMARY KEY (`id_boletim`);

--
-- Índices de tabela `boletins_disciplinas`
--
ALTER TABLE `boletins_disciplinas`
  ADD PRIMARY KEY (`id_boletim`,`id_disciplina`),
  ADD KEY `id_disciplina` (`id_disciplina`);

--
-- Índices de tabela `cidades`
--
ALTER TABLE `cidades`
  ADD PRIMARY KEY (`id_cidade`),
  ADD KEY `id_estado` (`id_estado`);

--
-- Índices de tabela `coordenadores`
--
ALTER TABLE `coordenadores`
  ADD PRIMARY KEY (`id_coordenador`),
  ADD KEY `id_dados` (`id_dados`),
  ADD KEY `id_rua` (`id_rua`);

--
-- Índices de tabela `cursos`
--
ALTER TABLE `cursos`
  ADD PRIMARY KEY (`id_curso`);

--
-- Índices de tabela `cursos_disciplinas`
--
ALTER TABLE `cursos_disciplinas`
  ADD PRIMARY KEY (`id_curso`,`id_disciplina`),
  ADD KEY `id_disciplina` (`id_disciplina`);

--
-- Índices de tabela `dados_pessoais`
--
ALTER TABLE `dados_pessoais`
  ADD PRIMARY KEY (`id_dados`);

--
-- Índices de tabela `disciplinas`
--
ALTER TABLE `disciplinas`
  ADD PRIMARY KEY (`id_disciplina`),
  ADD KEY `id_curso` (`id_curso`),
  ADD KEY `id_professor` (`id_professor`);

--
-- Índices de tabela `estados`
--
ALTER TABLE `estados`
  ADD PRIMARY KEY (`id_estado`);

--
-- Índices de tabela `matriculas`
--
ALTER TABLE `matriculas`
  ADD PRIMARY KEY (`id_matricula`),
  ADD KEY `id_aluno` (`id_aluno`),
  ADD KEY `id_turma` (`id_turma`);

--
-- Índices de tabela `matricula_curso`
--
ALTER TABLE `matricula_curso`
  ADD PRIMARY KEY (`id_matricula`,`id_curso`),
  ADD KEY `id_curso` (`id_curso`);

--
-- Índices de tabela `professores`
--
ALTER TABLE `professores`
  ADD PRIMARY KEY (`id_professor`),
  ADD KEY `id_dados` (`id_dados`),
  ADD KEY `id_rua` (`id_rua`);

--
-- Índices de tabela `responsaveis`
--
ALTER TABLE `responsaveis`
  ADD PRIMARY KEY (`id_responsavel`),
  ADD KEY `id_dados` (`id_dados`),
  ADD KEY `id_rua` (`id_rua`);

--
-- Índices de tabela `ruas`
--
ALTER TABLE `ruas`
  ADD PRIMARY KEY (`id_rua`),
  ADD KEY `id_bairro` (`id_bairro`);

--
-- Índices de tabela `telefones`
--
ALTER TABLE `telefones`
  ADD PRIMARY KEY (`id_telefone`),
  ADD KEY `id_dados` (`id_dados`);

--
-- Índices de tabela `turmas`
--
ALTER TABLE `turmas`
  ADD PRIMARY KEY (`id_turma`),
  ADD KEY `id_curso` (`id_curso`);

--
-- Restrições para tabelas despejadas
--

--
-- Restrições para tabelas `alunos`
--
ALTER TABLE `alunos`
  ADD CONSTRAINT `alunos_ibfk_1` FOREIGN KEY (`id_dados`) REFERENCES `dados_pessoais` (`id_dados`),
  ADD CONSTRAINT `alunos_ibfk_2` FOREIGN KEY (`id_rua`) REFERENCES `ruas` (`id_rua`);

--
-- Restrições para tabelas `alunos_responsaveis`
--
ALTER TABLE `alunos_responsaveis`
  ADD CONSTRAINT `alunos_responsaveis_ibfk_1` FOREIGN KEY (`id_aluno`) REFERENCES `alunos` (`id_aluno`),
  ADD CONSTRAINT `alunos_responsaveis_ibfk_2` FOREIGN KEY (`id_responsavel`) REFERENCES `responsaveis` (`id_responsavel`);

--
-- Restrições para tabelas `avaliacoes`
--
ALTER TABLE `avaliacoes`
  ADD CONSTRAINT `avaliacoes_ibfk_1` FOREIGN KEY (`id_disciplina`) REFERENCES `disciplinas` (`id_disciplina`);

--
-- Restrições para tabelas `bairros`
--
ALTER TABLE `bairros`
  ADD CONSTRAINT `bairros_ibfk_1` FOREIGN KEY (`id_cidade`) REFERENCES `cidades` (`id_cidade`);

--
-- Restrições para tabelas `boletins_disciplinas`
--
ALTER TABLE `boletins_disciplinas`
  ADD CONSTRAINT `boletins_disciplinas_ibfk_1` FOREIGN KEY (`id_boletim`) REFERENCES `boletins` (`id_boletim`),
  ADD CONSTRAINT `boletins_disciplinas_ibfk_2` FOREIGN KEY (`id_disciplina`) REFERENCES `disciplinas` (`id_disciplina`);

--
-- Restrições para tabelas `cidades`
--
ALTER TABLE `cidades`
  ADD CONSTRAINT `cidades_ibfk_1` FOREIGN KEY (`id_estado`) REFERENCES `estados` (`id_estado`);

--
-- Restrições para tabelas `coordenadores`
--
ALTER TABLE `coordenadores`
  ADD CONSTRAINT `coordenadores_ibfk_1` FOREIGN KEY (`id_dados`) REFERENCES `dados_pessoais` (`id_dados`),
  ADD CONSTRAINT `coordenadores_ibfk_2` FOREIGN KEY (`id_rua`) REFERENCES `ruas` (`id_rua`);

--
-- Restrições para tabelas `cursos_disciplinas`
--
ALTER TABLE `cursos_disciplinas`
  ADD CONSTRAINT `cursos_disciplinas_ibfk_1` FOREIGN KEY (`id_curso`) REFERENCES `cursos` (`id_curso`),
  ADD CONSTRAINT `cursos_disciplinas_ibfk_2` FOREIGN KEY (`id_disciplina`) REFERENCES `disciplinas` (`id_disciplina`);

--
-- Restrições para tabelas `disciplinas`
--
ALTER TABLE `disciplinas`
  ADD CONSTRAINT `disciplinas_ibfk_1` FOREIGN KEY (`id_curso`) REFERENCES `cursos` (`id_curso`),
  ADD CONSTRAINT `disciplinas_ibfk_2` FOREIGN KEY (`id_professor`) REFERENCES `professores` (`id_professor`);

--
-- Restrições para tabelas `matriculas`
--
ALTER TABLE `matriculas`
  ADD CONSTRAINT `matriculas_ibfk_1` FOREIGN KEY (`id_aluno`) REFERENCES `alunos` (`id_aluno`),
  ADD CONSTRAINT `matriculas_ibfk_2` FOREIGN KEY (`id_turma`) REFERENCES `turmas` (`id_turma`);

--
-- Restrições para tabelas `matricula_curso`
--
ALTER TABLE `matricula_curso`
  ADD CONSTRAINT `matricula_curso_ibfk_1` FOREIGN KEY (`id_matricula`) REFERENCES `matriculas` (`id_matricula`),
  ADD CONSTRAINT `matricula_curso_ibfk_2` FOREIGN KEY (`id_curso`) REFERENCES `cursos` (`id_curso`);

--
-- Restrições para tabelas `professores`
--
ALTER TABLE `professores`
  ADD CONSTRAINT `professores_ibfk_1` FOREIGN KEY (`id_dados`) REFERENCES `dados_pessoais` (`id_dados`),
  ADD CONSTRAINT `professores_ibfk_2` FOREIGN KEY (`id_rua`) REFERENCES `ruas` (`id_rua`);

--
-- Restrições para tabelas `responsaveis`
--
ALTER TABLE `responsaveis`
  ADD CONSTRAINT `responsaveis_ibfk_1` FOREIGN KEY (`id_dados`) REFERENCES `dados_pessoais` (`id_dados`),
  ADD CONSTRAINT `responsaveis_ibfk_2` FOREIGN KEY (`id_rua`) REFERENCES `ruas` (`id_rua`);

--
-- Restrições para tabelas `ruas`
--
ALTER TABLE `ruas`
  ADD CONSTRAINT `ruas_ibfk_1` FOREIGN KEY (`id_bairro`) REFERENCES `bairros` (`id_bairro`);

--
-- Restrições para tabelas `telefones`
--
ALTER TABLE `telefones`
  ADD CONSTRAINT `telefones_ibfk_1` FOREIGN KEY (`id_dados`) REFERENCES `dados_pessoais` (`id_dados`);

--
-- Restrições para tabelas `turmas`
--
ALTER TABLE `turmas`
  ADD CONSTRAINT `turmas_ibfk_1` FOREIGN KEY (`id_curso`) REFERENCES `cursos` (`id_curso`);
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
