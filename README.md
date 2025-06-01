<h2>Problema:</h2>
<p>Desenvolver uma solução capaz de detectar ciclos em grafos, utilizando algoritmos apropriados para geração e análise de grafos direcionados ou não direcionados.</p>

<h2>Planejamento:</h2>
<ol>
  <li><strong>Estudo e Definição da Geração de Grafos</strong>
    <ol>
      <li>Pesquisa e análise de algoritmos para geração de grafos</li>
      <li>Escolha ou desenvolvimento do algoritmo mais adequado ao propósito do projeto</li>
      <li>Implementação/adaptação do algoritmo gerador</li>
    </ol>
  </li>
  <li><strong>Estudo e Definição da Detecção de Ciclos</strong>
    <ol>
      <li>Levantamento de algoritmos existentes para detecção de ciclos</li>
      <li>Avaliação das alternativas considerando tipo de grafo, complexidade e aplicabilidade</li>
      <li>Escolha do algoritmo mais apropriado</li>
      <li>Implementação/adaptação do algoritmo selecionado</li>
    </ol>
  </li>
  <li><strong>Integração e Desenvolvimento do Sistema</strong>
    <ol>
      <li>Integração dos algoritmos de geração e detecção</li>
      <li>Criação de interface para visualização ou uso do sistema - (talvez com monogame)</li>
    </ol>
  </li>
  <li><strong>Testes e Validação</strong>
    <ol>
      <li>Elaboração de casos de teste com e sem ciclos</li>
      <li>Verificação da correção dos resultados</li>
      <li>Avaliação de desempenho em diferentes tamanhos e tipos de grafos</li>
      <li>Ajustes finais</li>
    </ol>
  </li>
</ol>

<h2>Cronograma:</h2>
<table>
  <thead>
    <tr>
      <th>Fase</th>
      <th>Atividades</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1ª</td>
      <td>Planejamento e Estudo Inicial</td>
    </tr>
    <tr>
      <td>2ª</td>
      <td>Geração de Grafos</td>
    </tr>
    <tr>
      <td>3ª</td>
      <td>Detecção de Ciclos - Pesquisa e Escolha do Algoritmo</td>
    </tr>
    <tr>
      <td>4ª</td>
      <td>Implementação da Detecção de Ciclos</td>
    </tr>
    <tr>
      <td>5ª</td>
      <td>Testes e Validação</td>
    </tr>
  </tbody>
</table>
<h2>Resultados Obtidos:</h2>
<h3>Dia 1</h3>
<h4>Definição incial algoritmo detecção: Uso do algoritmo DFS with backtracking</h4>
<p>Motivos: Implemetação mais simples, amplamente utilizado para este fim, aplicavel para gráfos direcionados e não-direcionados</p>
<h4>Escolha de alternativas para a geração de gráfos</h4>
<p>Possibilidades: QuickGraph, biblioteca C# para estruturas de dados de grafos e algoritmos relacionados, com algoritmos prontos para geração de grafos aleatórios, busca em largura e profundidade. Outra alternativa seria criar o próprio algoritmo gerador de gráfos, pois permite uma maior flexibilidade, controle e personalização</p>