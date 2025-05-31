# Projeto ETL com API ViaCEP
## Projeto ETL com API ViaCEP

Este projeto tem como objetivo realizar uma extração e consolidação de dados de clientes utilizando a API pública do [ViaCEP](https://viacep.com.br/).

## 🔍 Objetivo

- Carregar um arquivo `.csv` com CEPs de clientes.
- Consultar cada CEP na API do ViaCEP.
- Enriquecer os dados com informações de logradouro, bairro, cidade e UF.
- Salvar os dados enriquecidos em um novo arquivo `.csv`.

## 🧰 Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Requests
- API ViaCEP

## ⏱️ Observações
A API do ViaCEP é gratuita, mas tem limite de requisições por segundo. Por isso, usamos time.sleep(1) para evitar bloqueios.
Valores ausentes foram tratados como 'Não cadastrado'.

## 📌 Autor
Este projeto foi criado para fins de aprendizado e demonstração de habilidades em Python e ETL com APIs públicas.
