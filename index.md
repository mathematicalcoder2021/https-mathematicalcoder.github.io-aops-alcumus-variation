<html>
 <head>
    <title>Random Problem Generator</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.13.11/dist/katex.min.css" integrity="sha384-Um5gpz1odJg5Z4HAmzPtgZKdTBHZdw8S29IecapCSB31ligYPhHQZMIlWLYQGVoc" crossorigin="anonymous">
    <script defer src="https://cdn.jsdelivr.net/npm/katex@0.13.11/dist/katex.min.js" integrity="sha384-YNHdsYkH6gMx9y3mRkmcJ2mFUjTd0qNQQvY9VYZgQd7DcN7env35GzlmFaZ23JGp" crossorigin="anonymous"></script>
    <script defer src="https://cdn.jsdelivr.net/npm/katex@0.13.11/dist/contrib/auto-render.min.js" integrity="sha384-vZTG03m+2yp6N6BNi5iM4rW4oIwk5DfcNdFfxkk9ZWpDriOkXX8voJBFrAO7MpVl" crossorigin="anonymous"
        onload="renderMathInElement(document.body);">
 </head>
 <body>
 <h1>Problem</h1>
 <p id="load">Problem is loading... please wait!</p>
 <script>
 let p1 = "Luka is making lemonade to sell at a school fundraiser. His recipe requires $4$ times as much water as sugar and twice as much sugar as lemon juice. He uses $3$ cups of lemon juice. How many cups of water does he need?";
 let pno = Math.floor(Math.random() * 1);
 if (pno == 0) {
  document.getElementById("p1").innerHTML = p1;

 }
 </script>
 </body>
</html>
