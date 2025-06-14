# Meu Currículo

Este repositório contém o código fonte do meu currículo profissional, desenvolvido em LaTeX.

## 📋 Sobre

Este projeto utiliza LaTeX para criar um currículo profissional bem formatado e facilmente atualizável. O arquivo principal é `Curriculo.tex`, que gera o PDF final do currículo.

## 🛠️ Tecnologias Utilizadas

- LaTeX
- Docker (para ambiente de desenvolvimento)

## 🚀 Como Usar

### Pré-requisitos

- Docker instalado em sua máquina
- Git

### Configuração do Ambiente

1. Clone este repositório:
```bash
git clone https://github.com/bodescorp/MyCurriculo.git
```

2. Entre no diretório do projeto:
```bash
cd MyCurriculo
```

3. O projeto utiliza um container Docker para desenvolvimento. O VS Code com a extensão "Remote - Containers" irá automaticamente configurar o ambiente ao abrir o projeto.

### Configuração de Submódulo e Link Simbólico

1. Inicialize e atualize o submódulo:
```bash
git submodule init
git submodule update
```

2. Crie o link simbólico para o diretório Documents:
```bash
    ln -s Documents/.devcontainer .devcontainer
    ln -s Documents/DockerFile DockerFile
```

### Compilando o Currículo

1. Com o ambiente configurado, você pode compilar o currículo usando:
```bash
pdflatex Curriculo.tex
```

2. O arquivo PDF será gerado como `Curriculo.pdf`

## 📁 Estrutura do Projeto

- `Curriculo.tex` - Arquivo principal do currículo
- `Documents/` - Diretório contendo documentos auxiliares
- `.devcontainer/` - Configurações do ambiente de desenvolvimento
- `DockerFile` - Configuração do container Docker

## 📝 Licença

Este projeto está sob a licença incluída no arquivo `LICENSE`.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests. 