<h1>Console Tricks (Truques de Console em JavaScript)</h1>
<p>Este projeto demonstra diversos truques e recursos úteis do console do navegador em JavaScript. Ele inclui exemplos de como usar o console para exibir mensagens de diferentes tipos, agrupar informações, contar ocorrências, medir o tempo de execução de tarefas e visualizar elementos do DOM em formato de tabela.</p>

<h4>Funcionalidades</h4>
<li><code>console.log("hello");</code> // Log simples: Exibe uma mensagem básica no console.</li>
<li><code>console.log("Hello I am a %s string!", "💩");</code> // Log interpolado: Insere valores em uma string de log usando placeholders (%s).</li>
<li><code>console.log('%c I am some great text', 'font-size:50px; background:red; text-shadow: 10px 10px 0 blue')</code> // Log estilizado: Aplica estilos CSS à mensagem de log (tamanho da fonte, cor de fundo, sombra de texto, etc.).</li>
<li><code>console.warn("OH NOOO");</code> // Avisos: Exibe mensagens de aviso.</li>
<li><code>console.error("Shit!");</code> // Erros :|: Exibe mensagens de erro.</li>
<li><code>console.info("Crocodiles eat 3-4 people per year");</code> // Informações: Exibe mensagens informativas.</li>
<li><code>console.assert(p.classList.contains("ouch"), "That is wrong!");</code> // Testes: Verifica se uma condição é verdadeira e exibe um erro caso contrário.</li>
<li><code>console.clear();</code> // Limpar o console: Limpa todas as mensagens do console.</li>
<li><code>console.log(p);</code></li> <li><code>console.dir(p);</code> // Visualizar elementos do DOM: Exibe informações sobre um elemento do DOM.</li>
<li><code>console.groupCollapsed(${dog.name});</code></li> <li><code>console.log(This is ${dog.name});</code></li> <li><code>console.log(${dog.name} is ${dog.age} years old);</code></li> <li><code>console.log(${dog.name} is ${dog.age * 7} dog years old);</code></li> <li><code>console.groupEnd(${dog.name});</code> // Agrupamento: Agrupa mensagens de log relacionadas em um bloco colapsável.</li>
<li><code>console.count("Caio");</code> // Contagem: Conta quantas vezes uma determinada mensagem foi registrada.</li>
<li><code>console.time("fetching data");</code></li> <li><code>fetch("https://api.github.com/users/Caiorossi00")</code></li> <li><code>.then((data) => data.json())</code></li> <li><code>.then((data) => {</code></li> <li><code>console.timeEnd("fetching data");</code></li> <li><code>console.log(data);</code></li> <li><code>});</code> // Medição de tempo: Mede o tempo de execução de uma tarefa.</li>
<li><code>console.table(dogs);</code> // Visualização em tabela: Exibe dados em formato de tabela.</li>
<br/>
Datas Importantes:
<li>Início: 12/03/2024</li>
<li>Final: 12/03/2024</li>

Link: <a href="https://caiorossi00.github.io/Dev-tools/">Console Tricks</a>
