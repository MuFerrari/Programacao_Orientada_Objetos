# ☕ Programação Orientada a Objetos (POO) ☕

<div align="center">
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/NetBeans-1B6AC6.svg?style=for-the-badge&logo=apache-netbeans&logoColor=white" alt="NetBeans">
</div>

<div align="justify">

  <br></br>
  
  Bem-vindo ao meu repositório de Programação Orientada a Objetos! Este diretório documenta a minha evolução, conceitos estudados e os projetos práticos desenvolvidos durante a disciplina. 
  
  <br></br>
  
  
  ## 🧠 O Que Aprendi Até Aqui (Conceitos & Analogias)
  
  A construção dos **Projetos presentes no Diretório** permitiu a consolidação dos seguintes pilares da POO:
  
  1. **Classes e Objetos**
     * **Conceito:** A classe `Aluno.java` atua como a *planta arquitetônica* do projeto. Ela não é um aluno real, mas dita as regras: define o que o aluno *tem* (atributos como Nome e RA) e o que ele *faz* (métodos como calcular a média).
     * **Prática:** Dentro do arquivo `Aplic.java`, essa planta é utilizada para erguer *casas* reais. É ali que instanciamos os objetos (ex: `Aluno aluno1 = new Aluno();`), dando vida aos dados na memória.
  
  2. **Pacotes e Separação Lógica**
     * A utilização do pacote `fatec.poo.model` demonstra a importância da organização estrutural. Em vez de deixar todos os arquivos espalhados na mesma "pasta", criamos "subpastas" específicas. O pacote *model* serve estritamente para guardar a lógica e a estrutura da entidade, isolando-a da classe que executa o software.
  
  3. **Ciclo de Vida do Código (IDE e Build)**
     * Compreensão de como o código-fonte (pasta `src/`) é transformado em linguagem de máquina (arquivos `.class` na pasta `build/class/`) e gerenciado automaticamente pela IDE.
  
  <br></br>
  
  ## 📂 Arquiteturas e Estruturas
  Os projetos adota boas práticas de separação de responsabilidades, dividindo o código de forma semântica:
  * **`src/fatec/poo/model/Aluno.java`**: A classe de domínio que representa a entidade central do sistema.
  * **`src/Aplic.java`**: A classe executável (Main) responsável por rodar o programa e interagir com o modelo.
  
  <br></br>
  
  ## ⚙️ Como Executar os Projetos
  
  1. Clone este repositório: `git clone <URL_DO_SEU_REPOSITORIO>`
  2. Abra a pasta do projeto desejado na sua IDE.
  3. Compile o projeto e execute o arquivo principal (geralmente nomeado como `Aplic.java` ou `Main.java`).
  
  <br></br>
  
  ## 🛠️ Tecnologias Utilizadas
  * **Linguagem:** Java;
  * **Paradigma:** Programação Orientada a Objetos;
  * **Ecossistema:** NetBeans 🫘;
</div>
