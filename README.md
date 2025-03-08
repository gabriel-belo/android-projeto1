# android-projeto1

Activities são o ponto de entrada de um App

Em Apps Android, não tem um método main, ou seja, utilizamos Activities para inicializar nosso App

O que compõem uma Activity:
-View: um Layout visual apresentado para o usuário
-Lógica: É a lógica que fara com que o aplicativo possa fazer coisas, é o código fonte Java no caso do projeto, no projeto teremos a atribuição de uma ação a um componente lógico, iremos adicionar aluno ou alunos na lista 

dentro da pasta java teremos nossos pacotes, o primeiro será o código de produção(código executado e apresentado para o usuário), os dois pacacots androidTest e test são pacotes direcionados para testes, faremos testes de aplicações que queremos adicionar ao nosso aplicativo nele

Para identificar que é uma Activity do Android precisamos utilizar a herança, iremos então herdar de uma classe chamada Activity, extends Activity

No AndroidManifest podemos fazer a configuração dos componentes principais do aplicativo. dentro do AndroidManifest ja temos o application que é o componente principal do aplicativo é por meio dele que ira manter o estado global do nosso aplicativo, temos que colocar os componentes dentro do aplication
No aplication nós adicionamos as Activitys e dentro das Activitys adicionamos um filtro de intenção (intent-filter) dentro de intent-filter colocamos a ação(action) e também aficionamos a categoria(category) que é o tipo de ação que irá executar, no caso do projeto é de lançador

