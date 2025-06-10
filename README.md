# Template LaTeX para Dissertações e Teses do Programa de Pós-Graduação em Música - UFMG

Este repositório contém um template LaTeX desenvolvido para facilitar a elaboração de documentos acadêmicos (dissertações, teses, relatórios) no âmbito do Programa de Pós-Graduação em Música da Universidade Federal de Minas Gerais (UFMG).

---

## Estrutura do Template

- O arquivo principal é o `main.tex`, que carrega todos os demais arquivos do projeto.
- A tese foi dividida em blocos, onde cada capítulo está em um arquivo `.tex` independente, localizado dentro da pasta `arquivos/`, por exemplo:
  - `arquivos/introducao.tex`
  - `arquivos/metodologia.tex`
  - `arquivos/discussao.tex`
- Há um arquivo chamado `dados.tex` onde você deve inserir suas informações pessoais e do trabalho, como:
  - Nome do autor
  - Título da tese
  - Nome do orientador
- Você pode adicionar suas figuras dentro de pastas e importá-las de maneira organizada.
- Você pode adicionar arquivos .pdf e importá-los dentro do main.tex.

- Para as referências bibliográficas, utilize o arquivo `bib.bib`. Atualize-o com as referências do seu trabalho.
- O glossário está separado em um arquivo chamado `glossario.tex`, que deve ser editado conforme necessário.
- Além dos capítulos, o template inclui uma série de arquivos pré-textuais e pós-textuais, tais como:
  - Capa e folha de rosto (estes arquivos devem ser substituídos pela versão atual do programa)
  - Epígrafe
  - Agradecimentos
  - Anexos
  - Entre outros elementos padrão de uma tese

---

## Como usar

### Opção 1: Clonar o repositório

1. Clone este repositório:
   ```bash
   git clone https://github.com/ivanmoria/LaTeX_Template_PPG_Musica_UFMG.git
```
2. Acesse a pasta clonada:
```bash
cd LaTeX_Template_PPG_Musica_UFMG
```
3. Abra o arquivo main.tex no seu editor LaTeX preferido (ex: TeXstudio, VSCode com extensão LaTeX Workshop, Overleaf Desktop).

4. Compile o arquivo main.tex. Certifique-se de usar o modo PDFLaTeX ou XeLaTeX).

5. O PDF gerado estará na mesma pasta, com o nome definido no início do arquivo .tex.

### Opção 2: Baixar e importar no Overleaf

1. Acesse o repositório no GitHub:  
   [https://github.com/ivanmoria/LaTeX_Template_PPG_Musica_UFMG](https://github.com/ivanmoria/LaTeX_Template_PPG_Musica_UFMG)

2. Clique no botão verde `Code` e depois em **Download ZIP**.

3. Extraia o conteúdo do arquivo `.zip` no seu computador.

4. Acesse [https://www.overleaf.com](https://www.overleaf.com) e faça login ou crie uma conta gratuita.

5. No painel principal do Overleaf, clique em **"New Project"** → **"Upload Project"**.

6. Envie a **pasta inteira extraída** ou compacte novamente os arquivos em um `.zip` e envie esse `.zip`.

7. O Overleaf irá importar o projeto, e você poderá editar e compilar o arquivo `main.tex` diretamente na plataforma.


