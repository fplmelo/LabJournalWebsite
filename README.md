# Ecologia Numérica

## Ciências Biológicas - Bacharelado - UFPE

**Docentes responsáveis** <br>
Prof. Felipe Melo (Botânica) & Prof. José Roberto Botelho (Zoologia)

**Período** <br>2020.1

**Créditos** <br>
45 horas (4 créditos)


**Resumo** <br>Ecologia numérica é uma disciplina que trata da análise da biodiversidade em comunidades biológicas através
de técnicas de análise multivariada e índices de diversidade taxonômica, funcional e filogenética. A carga horária total será de 45 horas mas serão necessárias muitas horas de investimento extra-aula para que o estudante termine a disciplina com domínio mínimo de conceitos e ferramentas para a análise de dados ecológicos assim como domínio das técnicas e métodos para alcançar autonomia e produzir soluções para suas próprias questões relativas à análise de dados ecológicos utilizando a linguagem R.

---

### Informações aos participantes

**Datas e horários** <br>
Teórico-prático: 19/10 – 23/10 [09 h - 12 h | 14 h - 17 h] (30 horas)

Exercícios-atividades assistidas remotamente: 26/10 – 30/10 (30 horas)

**Plano de ensino** <br> 
[pdf](https://github.com/fplmelo/ecologia_numerica/blob/main/00_plano_ensino.pdf)

**Contato** <br>
Para mais informações ou dúvidas, envie e-mail para Felipe Melo (felipe.plmelo@ufpe.br)

---

### Instruções aos participantes

**Hardware** <br>
Será necessário que todos usem seus notebooks

**Softwares**<br>
R, RStudio e git <br>

1. Instalar a versão mais recente do [R (4.0.x)](https://www.r-project.org) e [RStudio (1.3.x)](https://www.rstudio.com) <br>
   [Vídeo de instalação do R e do RStudio](https://youtu.be/l1bWvZMNMCM) <br>
   [Curso da linguagem R](https://www.youtube.com/playlist?list=PLucm8g_ezqNq0RMHvzZ8M32xhopFhmsr6)

   

2. Instalar o [git (2.28)](https://git-scm.com/downloads)<br>
   [Vídeo de instalação do git](https://youtu.be/QSfHNEiBd2k) <br>

#### Linux (Ubuntu e Linux Mint)

```
# r
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu focal-cran40/"
sudo apt update
sudo apt install -y r-base r-base-core r-recommended r-base-dev

# r spatial
sudo add-apt-repository ppa:ubuntugis/ubuntugis-unstable
sudo apt update
sudo apt install -y libudunits2-dev libgdal-dev libgeos-dev libproj-dev

# rstudio
wget -c https://download1.rstudio.org/desktop/bionic/amd64/rstudio-1.3.1093-amd64.deb
sudo dpkg -i rstudio-1.3.1093-amd64.deb
sudo apt install -fy
rm rstudio-1.3.1093-amd64.deb

# git
sudo add-apt-repository ppa:git-core/ppa 
sudo apt update
sudo apt install -y git

```

**Instalar os pacotes no R** <br>
Com o R e o RStudio instalados, baixe esse [script](https://github.com/mauriciovancine/disciplina-analise-geoespacial-r/blob/master/02_scripts/00_script_install_packages.R) (scripts são roteiros que possuem comandos, como um rascunho). <br>
Abra o script (**00_script_install_r_packages.R**) no software RStudio e rode cada linha de comando para instalar os pacotes, necessário estar conectado à internet. <br>
Para rodar as linhas, basta colocar o cursor na linha de código a ser executada e pressionar: `Ctrl + Enter`.


---

## Slides

- [0 Apresentações](https://mauriciovancine.github.io/disciplina-analise-geoespacial-r/01_aulas/00_pres_intro_geocomp_r.html)
- [1 Controle de versão, Git e GitHub](https://mauriciovancine.github.io/disciplina-analise-geoespacial-r/01_aulas/01_pres_intro_geocomp_r.html)
- [2 Funcionamento da linguagem R](https://mauriciovancine.github.io/disciplina-analise-geoespacial-r/01_aulas/02_pres_intro_geocomp_r.html)
- [3 Estrutura e manipulação de dados](https://mauriciovancine.github.io/disciplina-analise-geoespacial-r/01_aulas/03_pres_intro_geocomp_r.html)
- [4 Introdução ao tidyverse](https://mauriciovancine.github.io/disciplina-analise-geoespacial-r/01_aulas/04_pres_intro_geocomp_r.html)
- [5 Estrutura e fonte de dados geoespaciais](https://mauriciovancine.github.io/disciplina-analise-geoespacial-r/01_aulas/05_pres_intro_geocomp_r.html)
- [6 Estrutura e manipulação de dados vetoriais](https://mauriciovancine.github.io/disciplina-analise-geoespacial-r/01_aulas/06_pres_intro_geocomp_r.html)
- [7 Estrutura e manipulação de dados matriciais](https://mauriciovancine.github.io/disciplina-analise-geoespacial-r/01_aulas/07_pres_intro_geocomp_r.html)
- [8 Produção de mapas](https://mauriciovancine.github.io/disciplina-analise-geoespacial-r/01_aulas/08_pres_intro_geocomp_r.html)

---

## Scripts

- [Instalar pacotes](https://github.com/mauriciovancine/disciplina-analise-geoespacial-r/blob/master/02_scripts/00_script_install_packages.R)
- [3 Estrutura e manipulação de dados](https://github.com/mauriciovancine/disciplina-analise-geoespacial-r/blob/master/02_scripts/03_script_intro_geocomp_r.R)
- [4 Introdução ao tidyverse](https://github.com/mauriciovancine/disciplina-analise-geoespacial-r/blob/master/02_scripts/04_script_intro_geocomp_r.R)
- [6 Estrutura e manipulação de dados vetoriais](https://github.com/mauriciovancine/disciplina-analise-geoespacial-r/blob/master/02_scripts/06_script_intro_geocomp_r.R)
- [7 Estrutura e manipulação de dados matriciais](https://github.com/mauriciovancine/disciplina-analise-geoespacial-r/blob/master/02_scripts/07_script_intro_geocomp_r.R)
- [8 Produção de mapas](https://github.com/mauriciovancine/disciplina-analise-geoespacial-r/blob/master/02_scripts/08_script_intro_geocomp_r.R)

---
