# CloudQuest


![image](https://github.com/Latamila/CloudQuest/blob/main/photos/screenshot_20260312232034.png
)
![image](https://github.com/Latamila/CloudQuest/blob/main/photos/screenshot_20260313005448.png)

![image](https://github.com/Latamila/CloudQuest/blob/main/photos/screenshot_20260313111936.png)

Configurei componentes de rede VPC, incluindo tabelas de roteametno, internet gateway e security groups, para permitir conectividae segura com a internet. 

Alterei as regras do security group para permitir o tráfego, pela porta 3306, no servidor de banco de dados MySQL/Aurora.
![image](https://github.com/Latamila/CloudQuest/blob/main/photos/Captura%20de%20tela%202026-03-13%20144951.png)


Neste Lab, criei uma estimativa de custos para uma arquitetura Amazon EC2 variável com base na demanda de pico. 
- Criei grupos lógicos de preços.
- Criei uma estimativa para uso do Amazon EC2.
- Alterei o tipo de instância do EC2 para t2.micro na estimativa de preços.
- Gerei este link e novos links a cada alteração para estimativa de preços. 

[Estimativa de Preço com t2.micro](https://calculator.aws/#/estimate?id=a19f6deff8d83ecb6d1f3a2a33b0eefd2f853f40)

[Estimativa de Preço com t3.micro](https://calculator.aws/#/estimate?id=11803e5cf1325c026111d40647b9893d9c73e3a9)


![image](https://github.com/Latamila/CloudQuest/blob/main/photos/Captura%20de%20tela%202026-03-13%20194551.png)

Neste Lab, implementei o VPC Peering para permitir comunicação entre VPCs, permitindo que as instâncias EC2 de Marketing e Desencvolvedores acessem o servidor de Serviços Financeiros na VPC de Finanças. 
- Configurei uma conexão de peering da VPC.
- Certifiquei através da Session Manager, de que o tráfego seja roteado corretamente entre as VPCs emparelhadas.
- O desafio maior foi configurar o emparelhamento entre as VPCs do desenvolvedor e do departamento financeiro, sozinha. Mas foi muito gratificante....
  
![image](https://github.com/Latamila/CloudQuest/blob/main/photos/Captura%20de%20tela%202026-03-14%20150418.png)

Nesse laboratório: 
- Migrei para o Amazon RDS para automatizar tarefas rotineras de administração de banco de dados;
- Implementei Multi-AZ e réplicas de leitura para fornecer alta disponibilidade e melhorar o desempenho.
- Explorei as ofertas de banco de dados da AWS.
- Iniciei uma instância do Amazon RDS.
- Configurei uma implantação Multi-AZ.
- Configurei backup do Amazon RDS.
- Criei uma réplica de leitura do banco de dados principal usando uma instância db.t3.xlarge. 

![image](https://github.com/Latamila/CloudQuest/blob/main/photos/Captura%20de%20tela%202026-03-15%20212033.png)

![image](https://github.com/Latamila/CloudQuest/blob/main/photos/Captura%20de%20tela%202026-03-15%20212354.png)

![image](https://github.com/Latamila/CloudQuest/blob/main/photos/Captura%20de%20tela%202026-03-15%20213319.png)

![image](https://github.com/Latamila/CloudQuest/blob/main/photos/Captura%20de%20tela%202026-03-15%20213331.png)




