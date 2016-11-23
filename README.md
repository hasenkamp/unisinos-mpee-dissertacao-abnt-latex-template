# unisinos-mpee-dissertacao-abnt-latex-template

Modelo de dissertação baseado no modelo ABNTex2 e sugerido para Mestrado Profissional em Engenharia Elétrica da Unisinos.

Para facilitar uso e edição em Latex sugerimos as ferramentas Overleaf e ShareLatex, ambos editores colaborativos online. Outros softwares offline também podem ser utilizados.

- Utilizar o arquivo "main.tex" como arquivo principal.

## Informações sobre os arquivos:

- 0-setup.tex - Informações de configuração e formatação do documento
- 1-dados.tex - Preencher com as informações relevantes
- 2-pretextual.tex - Diversas partes do documento antes de inicar os capítulos
- 3-postextual.tex - Anexos e apendices
- references.bib - Arquivo bibitex para referencias bibliográficas
- /images/* - Diretório utilizado para organizar as imagens utilizadas no documento
- /manuals/* - Alguns arquivos manuais para facilitar uso de alguns pacotes

## Tutorial para compilação offline:

- Faça o download dos seguintes softwares: Miktex (basic) e texStudio
- https://miktex.org/download
- http://www.texstudio.org/
- Instale o Miktex e selecione para instalar os pacotes automaticamente... Install Packages on the Fly = Yes
- Depois de instalado abra o "Miktex Package Manager (Admin)" e já instale os pacotes "abntex2" e o "cm-super".
- Instale o texstudio
- Faça o download dos arquivos do projeto no Overleaf "Download as ZIP"
- Descompacte no diretório de projeto desejado... use um diretório para cada projeto pois durante a compilação serão gerados diversos arquivos
- Abra o "main.tex" do projeto no texstudio e clique no icone >> para compilar o projeto... tecla de atalho = F5.
