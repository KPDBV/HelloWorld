<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HelloWorld in HTML, C#, C++</title>
  <style>
    body {
      background-color: #0d1117;
      color: #c9d1d9;
      font-family: Arial, sans-serif;
      margin: 40px;
    }
    a {
      color: #58a6ff;
      text-decoration: none;
    }
    h1, h2 {
      color: #ffffff;
    }
    pre {
      background-color: #161b22;
      padding: 10px;
      border-radius: 6px;
      overflow-x: auto;
    }
    code {
      color: #d2a8ff;
    }
    .donate {
      margin-top: 30px;
      background-color: #161b22;
      padding: 15px;
      border-left: 4px solid #3fb950;
    }
  </style>
</head>
<body>

<h1>HelloWorld in HTML, C#, C++</h1>

<p><strong>Why is this even a thing?</strong><br>
You ask because sometimes people forget how to write Hello World in HTML, C#, etc. So for that, I made this.</p>

<h2>HTML</h2>
<pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;
  &lt;h1&gt;Hello, World!&lt;/h1&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre>

<h2>C#</h2>
<pre><code>using System;

class Program {
    static void Main() {
        Console.WriteLine("Hello, World!");
    }
}
</code></pre>

<h2>C++</h2>
<pre><code>#include &lt;iostream&gt;

int main() {
    std::cout &lt;&lt; "Hello, World!" &lt;&lt; std::endl;
    return 0;
}
</code></pre>

<div class="donate">
  <h2>Donate Me:</h2>
  <p><strong>Bitcoin:</strong> bc1qxzmq4lcqk9vwr4jwv93t63elqd7uqgkpsr4r6p</p>
  <p><strong>Ethereum:</strong> 0x498C93cbffE96aFd5a016C9a52AC8E566b98F695</p>
  <p><strong>Solana:</strong> DVnStxgkgYnzM9CRYLyT9YdYFhs1dqrFNuaNT3bgu6Ny</p>
</div>

</body>
</html>
