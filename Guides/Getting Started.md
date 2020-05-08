# Primeiros Passos

### Passo-a-passo para criar um novo lote de processos e identificá-lo por uma tag correspondente.

1. Criar uma TAG para identificar o lote de processos em questão, utilizando o endpoint **tags/**
2. Caso exista uma “procuração” ou algum arquivo do tipo que seja comum a todos os arquivos no lote, adicionar esses arquivos com o endpoint **tag-files/**
3. Para adicionar os dados dos processos que fazem parte do lote pode ser enviado para nossa API uma planilha com os dados ou um JSON com os dados

    3a. O endpoint se chama: enrollments/batch/

    3b. O endpoint se chama: attachments/batch/