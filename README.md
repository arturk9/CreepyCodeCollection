# CreepyCodeCollection
#### A Nonsense Collection of Disgusting Codes

Here we are talking about creepiest of the most creepy codes. Programs, behave so strange, that they will twist your brain. Snippets, so small, that you won’t believe their functionality. And codes, so cryptic, that even the top coders will think of going back to the college.

**Note**: Never try this type of code in a real life software project; readability and maintainability should be the main concern there.


## Intro
See this cute little code ([↗](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/check_prime.pl))-

``` PL
(1x$a)!~/^1?$|^(11+?)\1+$/
```

In Perl, this regular expression checks if a number is prime.

Following code will produce day of the week for a given date ([↗](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/day_of_week.c))-

``` C
((y-=m<3)+y/4-y/100+y/400+" bed=pen+mad."[m]+d)%7
```

Consider this Java code ([↗](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/confusion.java))-

``` Java
int i = (byte) + (char) - (int) + (long) - 1;
```

What will be the value of `i`? Will the code even compile? Weird! Huh?

The program is a Ruby [Quine](https://en.wikipedia.org/wiki/Quine_(computing)) called qlobe ([↗](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/qlobe.rb)). Isn't the the output amazing?

  <div align="center">
    <img src="https://cloud.githubusercontent.com/assets/5456665/21362343/258441bc-c712-11e6-88bf-f8f02a028ad3.gif" alt="Qlobe" height="300" width=auto/>
  </div>

This is my favourite- The Animated 3d Doughnut ([↗](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/animated_3d_doughnut.c)). Taste how delicious it is!

  <div align="center">
    <img src="https://cloud.githubusercontent.com/assets/5456665/21362492/c976724a-c712-11e6-9773-03e80f8ba598.gif" alt="Animated 3d Doughnut" height="300" width=auto/>
  </div>
  
Paste this in your browser's url- 

    data:text/html,<body%20style=margin:0><canvas%20id=q%20/><script>var%20q=document.getElementById('q'),s=window.screen,w=q.width=s.width,h=q.height=s.height,p=Array(256).join(1).split(''),c=q.getContext('2d'),m=Math;setInterval(function(){c.fillStyle='rgba(0,0,0,0.05)';c.fillRect(0,0,w,h);c.fillStyle='rgba(0,255,0,1)';p=p.map(function(v,i){r=m.random();c.fillText(String.fromCharCode(m.floor(2720+r*33)),i*10,v);v+=10;%20return%20v>768+r*1e4?0:v})},33)</script>

And see the magic yourself ([↗](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/matrix_effect.html))!

Most of the programs here are hell hard to understand. The details-url provided with the codes contain useful description. Follow the [Creepy Rank](#creepy-rank) for getting a structured view of all the programs.

## Creepy Rank
Sorted by difficulty level-

### Level-1: Genin

[pyjava.java](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/pyjava.java) | Java code written like python. Finds factorial of big numbers.
[one_line_swap.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/one_line_swap.c) | Strange one-liners that swaps value of two variables.
[hello_world.java](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/hello_world.java) | Magically outputs "hello world" in the console.
[bangladesh.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/bangladesh.c) | Prints Map of Bangladesh. 
[obfuscated.java](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/obfuscated.java) | Prints "Hi!" in the console, looks like a big meaningless comment though.
  
### Level-2: Chunin
  - [bitwise_arithmetic.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/bitwise_arithmetic.c)
  - [prefix2postfix.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/prefix2postfix.c)
  - [crazy_jvm.java](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/crazy_jvm.java)
  - [confusion.java](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/confusion.java)
  - [not_so_random.java](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/not_so_random.java)
  - [signature_prime.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/signature_prime.c)
  - [day_of_week.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/day_of_week.c)
  - [polyglot_so404.py.pl.rb.c.bf](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/polyglot_so404.py.pl.rb.c.bf)
  - [polyglot_quine.c.py.pl.rb](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/polyglot_quine.c.py.pl.rb)

### Level-3: Jonin
  - [best_short_program.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/best_short_program.c)
  - [check_prime.pl](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/check_prime.pl)
  - [quine_signature.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/quine_signature.c)
  - [clock_in1line.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/clock_in1line.c)
  - [japh.pl](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/japh.pl)
  - [matrix_effect.html](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/matrix_effect.html)
  - [pi_signature.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/pi_signature.c)

### Level-4: Sannin
 - [mandelbrot_imager.py](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/mandelbrot_imager.py)
 - [shortest_tetris.html](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/shortest_tetris.html)
 - [qlobe.rb](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/qlobe.rb)
 - [animated_3d_doughnut.c](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/animated_3d_doughnut.c)
 - [mandelbrot_flythrough.pl](https://github.com/MinhasKamal/CreepyCodeCollection/blob/master/mandelbrot_flythrough.pl)

All the programs here have been tested (by me). [TutorialsPoint-CodingGround](https://www.tutorialspoint.com/codingground.htm) or [repl.it](https://repl.it/languages) has online code editors and compilers, which can be used to run these programs. Many programs here have been collected from q/a and discussion sites, like- [StackOverflow](stackoverflow.com), [Quora](https://www.quora.com/), [Programming Puzzles & Code Golf](http://codegolf.stackexchange.com/), & [Hacker News](https://news.ycombinator.com/news).

If you liked this project, then I am sure you will also love [CuteVirusCollection](https://github.com/MinhasKamal/CuteVirusCollection).


## Places for More Creepy Codes
- [IOCCC](http://www.ioccc.org/years-spoiler.html), [IOCCC Winning Entries](http://www.pixelstech.net/article/1351185934-Do-you-really-understand-C-21st-International-Obfuscated-C-Code-Contest-winning-entries)
- [PerlMonks](http://www.perlmonks.org)
- [C Cignature Programs](http://www.iwriteiam.nl/SigProgC.html)
- [CodeGolf-StackExchange: Tips](http://codegolf.stackexchange.com/questions/tagged/tips?sort=votes&pageSize=15), [CodeGolf-StackExchange: Quine](http://codegolf.stackexchange.com/questions/69/golf-you-a-quine-for-great-good), [StackOverflow: Strangest Language Feature](http://stackoverflow.com/questions/1995113/strangest-language-feature)
- [JS1K](http://js1k.com)
- [Quora: Elegant Code](https://www.quora.com/What-is-the-most-elegant-line-of-code-youve-seen), [Quora: Shortest Effective Code](https://www.quora.com/What-is-the-shortest-and-most-effective-code-ever-written), [Quora: Coolest Thing in 10 Line](https://www.quora.com/Whats-the-coolest-thing-you-can-get-a-computer-to-do-in-10-lines-of-code)
- [QuinePrograms](http://cs.lmu.edu/~ray/notes/quineprograms/)
- [CodePoetry](http://code-poetry.com/)
- [Anarchy Golf](http://golf.shinh.org/all.rb)
- http://uguu.org/sources.html
