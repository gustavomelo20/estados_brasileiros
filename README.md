# estados_brasileiros

$estados  = ["Acre",  "AC",  "Alagoas",  "AL",  "Amapá",  "AP",  "Amazonas",  "AM",  "Bahia",  "BA",  "Ceará",  "CE",  "Espírito Santo",  "ES",  "Goiás",  "GO",  "Maranhão",  "MA",  "Mato Grosso",  "MT",  "Mato Grosso do Sul",  "MS",  "Minas Gerais",  "MG",  "Pará",  "PA",  "Paraíba",  "PB",  "Paraná",  "PR",  "Pernambuco",  "PE",  "Piauí",  "PI",  "Rio de Janeiro",  "RJ",  "Rio Grande do Norte",  "RN",  "Rio Grande do Sul",  "RS",  "Rondônia",  "RO",  "Roraima",  "RR",  "Santa Catarina",  "SC",  "São Paulo", "SP",  "Sergipe",  "SE",  "Tocantins",  "TO",  "Distrito Federal",  "DF"];

for ($i=0; $i < count($estados) ; $i++) { 
     echo  "INSERT INTO estados (estado, uf)
     VALUES ('".$estados[$i]."' ,'".$estados[$i+1]."');<br>";
     $i++;
  }

INSERT INTO estados (estado, sigla) VALUES ('Acre' ,'AC');
INSERT INTO estados (estado, sigla) VALUES ('Alagoas' ,'AL');
INSERT INTO estados (estado, sigla) VALUES ('Amapá' ,'AP');
INSERT INTO estados (estado, sigla) VALUES ('Amazonas' ,'AM');
INSERT INTO estados (estado, sigla) VALUES ('Bahia' ,'BA');
INSERT INTO estados (estado, sigla) VALUES ('Ceará' ,'CE');
INSERT INTO estados (estado, sigla) VALUES ('Espírito Santo' ,'ES');
INSERT INTO estados (estado, sigla) VALUES ('Goiás' ,'GO');
INSERT INTO estados (estado, sigla) VALUES ('Maranhão' ,'MA');
INSERT INTO estados (estado, sigla) VALUES ('Mato Grosso' ,'MT');
INSERT INTO estados (estado, sigla) VALUES ('Mato Grosso do Sul' ,'MS');
INSERT INTO estados (estado, sigla) VALUES ('Minas Gerais' ,'MG');
INSERT INTO estados (estado, sigla) VALUES ('Pará' ,'PA');
INSERT INTO estados (estado, sigla) VALUES ('Paraíba' ,'PB');
INSERT INTO estados (estado, sigla) VALUES ('Paraná' ,'PR');
INSERT INTO estados (estado, sigla) VALUES ('Pernambuco' ,'PE');
INSERT INTO estados (estado, sigla) VALUES ('Piauí' ,'PI');
INSERT INTO estados (estado, sigla) VALUES ('Rio de Janeiro' ,'RJ');
INSERT INTO estados (estado, sigla) VALUES ('Rio Grande do Norte' ,'RN');
INSERT INTO estados (estado, sigla) VALUES ('Rio Grande do Sul' ,'RS');
INSERT INTO estados (estado, sigla) VALUES ('Rondônia' ,'RO');
INSERT INTO estados (estado, sigla) VALUES ('Roraima' ,'RR');
INSERT INTO estados (estado, sigla) VALUES ('Santa Catarina' ,'SC');
INSERT INTO estados (estado, sigla) VALUES ('São Paulo' ,'SP');
INSERT INTO estados (estado, sigla) VALUES ('Sergipe' ,'SE');
INSERT INTO estados (estado, sigla) VALUES ('Tocantins' ,'TO');
INSERT INTO estados (estado, sigla) VALUES ('Distrito Federal' ,'DF');
