# Matheus Bandeira de Oliveira
Repositório criado com o objetivo de facilitar o contato com a Inmetrics.

<p><h2>Explicando a automação em web:</h2></p>
  <p>Para o desafio foi criada a automação de todos os cenários propostos levando em consideração um fluxo "correto" e "incorreto" com as diversas possibilidades de digitação e erros, mesmo com o uso do cucumber foi criada uma DSL para facilitar a escrita da automação. Decidi dividir o projeto em 4 partes para uma melhor organização:</p>
   <ul> 
   <li><b>CORE</b>: Nesta pasta ficam as classes responsáveis por inicializar o chromedriver, os métodos da DSL, ou seja, tudo que é responsável para a inicialização do projeto.</li>
   <li><b>PAGES</b>: Local onde ficam as páginas com seus objetos mapeados.</li>
   <li><b>CENARIOS</b>:Onde ficam as classes .feature.</li>
   <li><b>TESTS</b>: Pasta onde encontra-se os arquivos .feature e suas classes em java.</li>
  </ul>
  
  <p>O objetivo foi criar um framework de testes e auxiliar a automação, os prints serão armazenados na pasta <b>"prints"</b> onde basta somente chamar o método print que está presente na DSL, as classes presentes no pacote <b>pages</b> funcionam como um repositório de objetos para determinado fluxo e podem ser utilizadas em outros fluxos, somente sendo necessário criar a instância na classe de teste.</p>
  <p>Foi criada também uma classe para facilitar a criação de massas de testes chamada de CreateData, ela contém 3 métodos que auxiliam a escrita para possíveis testes, o método <b>criarCpf</b> foi retirado do <a href="https://www.guj.com.br/t/gerador-de-cpf-cnpj-e-rg/208421/3">link gerador de cpf</a> já os outros 2 foram de criação minha.</p>
  <p>No projeto também encontra-se uma ENUM que são referentes as possibilidades de pastas para o armazenamento dos prints, fazendo com que o tester não erre na hora de nomear essas pastas.</p>
  
