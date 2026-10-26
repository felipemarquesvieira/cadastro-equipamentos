
# Cadastro de Equipamentos em C

## Descrição

Programa simples em linguagem C para cadastrar equipamentos,
salvar seus nomes e números de patrimônio em um arquivo de texto
e consultar os registros cadastrados.

## Funcionalidades

- Cadastrar equipamentos.
- Salvar os registros em equipamentos.txt.
- Listar os equipamentos cadastrados.
- Encerrar o programa pelo menu.

## Requisitos

- Compilador C, como GCC.
- Terminal ou prompt de comando.

## Como compilar

No terminal, dentro da pasta do projeto, execute:

```bash
gcc cadastro_equipamentos.c -o cadastro_equipamentos
```

## Como executar

No Linux ou macOS:

```bash
./cadastro_equipamentos
```

No Windows:

```bash
cadastro_equipamentos.exe
```

## Como utilizar

1. Escolha 1 para cadastrar um equipamento.
2. Digite o nome do equipamento.
3. Digite o número do patrimônio.
4. Escolha 2 para listar os registros.
5. Escolha 0 para sair.

Os novos registros são acrescentados ao arquivo
equipamentos.txt, sem apagar os anteriores.

## Autor

Nome do aluno: [Felipe Marques Vieira]
