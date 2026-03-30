🔄 Inversão de Nomes em C#

Um programa simples feito em C# que recebe quatro nomes do usuário e exibe esses nomes na ordem inversa.

🚀 Como funciona

O programa é dividido em três etapas principais:

🧾 Entrada de dados

O usuário digita quatro nomes:

Nome 1
Nome 2
Nome 3
Nome 4

Esses valores são armazenados em variáveis do tipo string.

🔁 Inversão dos nomes

O programa utiliza uma variável auxiliar para trocar os valores:

O primeiro nome troca com o quarto
O segundo nome troca com o terceiro

Isso é feito usando uma variável chamada auxiliar, que guarda temporariamente um valor durante a troca.

💬 Exibição do resultado

Após a inversão, o programa mostra os nomes na nova ordem:

👉 Nome4 → Nome3 → Nome2 → Nome1

Além disso, o Console.ReadKey() faz o programa esperar uma tecla antes de fechar.

💻 Execução
✅ Pré-requisitos
Ter o .NET SDK ou Visual Studio instalado
▶️ Passos
Crie um arquivo chamado:
Program.cs
Cole o código dentro dele
Execute o programa:

No terminal:

dotnet run

Ou no Visual Studio:

Pressione F5
💡 Dica

Esse método funciona bem para poucos nomes, mas se quiser inverter uma lista maior, o ideal é usar arrays ou listas, que tornam o código muito mais flexível 😉
