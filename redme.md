# OnePage - Análise e Automação de Indicadores de Vendas.

## Descrição

O projeto OnePage é uma aplicação em Python desenvolvida para calcular e enviar indicadores de vendas por e-mail para diferentes lojas. A aplicação processa dados de vendas de diversas lojas e calcula indicadores importantes, como faturamento, diversidade de produtos e ticket médio. Em seguida, gera um e-mail personalizado para cada loja, contendo os indicadores calculados e anexa uma planilha com os dados detalhados.

## Tecnologias Utilizadas
Python: A linguagem de programação principal para o desenvolvimento do projeto.
Pandas: Biblioteca para manipulação e análise de dados.
SMTP: Protocolo de envio de e-mails utilizado para o envio das notificações.
smtplib: Biblioteca Python para envio de e-mails via servidor SMTP.
Path: Biblioteca utilizada para tratar os arquivos e diretórios do projeto.

## Funcionalidades

### Cálculo de Indicadores

O projeto processa os dados de vendas de cada loja e calcula os seguintes indicadores:

#### 1. Faturamento:

* Faturamento acumulado no ano.
* Faturamento no dia específico.

#### 2. Diversidade de Produtos:

* Quantidade de produtos únicos vendidos ao longo do ano.
* Quantidade de produtos únicos vendidos no dia específico.

#### 3. Ticket Médio:

* Valor médio das compras ao longo do ano.
* Valor médio das compras no dia específico.

### 4. Geração de E-mails Personalizados:

O projeto gera e-mails personalizados para cada loja, contendo:

* Saudação ao gerente da loja.
* Indicadores calculados para o dia específico e acumulados no ano.
* Comparação dos indicadores com as metas estabelecidas, destacando em vermelho quando as metas não são atingidas.
* Tabelas formatadas em HTML para melhor visualização dos indicadores.
* Anexo de uma planilha contendo os dados detalhados.

### Envio de E-mails

* O projeto utiliza as configurações de servidor SMTP do Gmail para enviar os e-mails personalizados para os destinatários corretos. Ele anexa a planilha de dados à mensagem e realiza o envio do e-mail.

## Utilização

1. Certifique-se de ter o Python instalado em sua máquina.
2. Instale as bibliotecas necessárias.
3. Configure as informações do servidor SMTP, e-mail remetente e senha no código.
4. Substitua as variáveis dia_indicador, meta_faturamento_dia, meta_faturamento_ano, etc., pelas informações corretas.
5. Execute o script Python para calcular os indicadores, gerar os e-mails e enviá-los.


## Licença

[MIT](https://choosealicense.com/licenses/mit/)



## 💬 Contato
Eu sou um desenvolvedor em busca de uma carreira de sucesso, entre em contato para conversarmos:

https://www.linkedin.com/in/joaovitornsouza/
