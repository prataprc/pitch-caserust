@title[Rust introduction]

@snap[midpoint text-center slide1 span-60]
<h1>A case for Rust</h1>
From boot-loaders to browser applications.
@snapend


@snap[south-east author-box]
@fa[envelope](prataprc@gmail.com - R Pratap Chakravarthy) <br/>
@snapend

---

Why language ?
==============

<br/>

@snap[fragment text-center]
@color[gray](A good carpenter is only as good as his tools.)
@snapend

<br/>

@snap[fragment text-center]
And programming language is the @color[blue](#1) tool for everything that
involves a computer.
@snapend

<br/>

@snap[fragment text-center]
This case study is also going to be a case in history !
@snapend

---

Why program ?
=============

@snap[west text-blue fragment]
Call it Algorithms
@snapend

@snap[east text-green fragment]
Call it Data mining
@snapend

@snap[mt40 center text-center text-brown fragment]
Call it Artificial Intelligence
@snapend

@snap[why-program-1 fragment]
The need for programming arises because
@snapend

@snap[why-program-2 text-center text-gray fragment]
We want to automate repeatitive jobs, we need logic, we need mathematics
and bunch of electronics.
@snapend

---

Gold rush ?
===========

@snap[mt20 text-center fragment]
Close to @color[blue](700+) languages are being developed and maintained in past 50 years.
@snapend

@snap[mt20 text-center fragment]
Some of them are dead.
@snapend

@snap[mt20 text-center fragment]
@color[gray](Is this a gold rush ? Or some thing else ?)
@snapend

---

Not a gold rush! Just market
============================

@snap[mt20 size-80 text-center fragment]
@quote[Over time a market will split into two or more markets.](Immutable laws of marketing)
@snapend

@snap[mt20 text-center fragment]
The market for automating repeatitive jobs are no different.
@snapend

@snap[mt20 text-center fragment]
Program automata are nuanced and when the demand for
@color[gray](efficiency) and @color[gray](quality) is adequately pronounced,
for a particular nuance
@snapend

@snap[mt20 text-blue text-center fragment]
The market shall split !
@snapend

Note:
- Give an example

---

The dilemma
===========

<br/>
@snap[text-gray fragment]
Learn a dozen language to become a good carpenter.
@snapend

@snap[mt20 fragment]
OR
@snapend

@snap[mt20 text-green fragment]
Just one language and be stuck in the same workshop
@snapend

---

Neither !
=========

@snap[mt20 text-center fragment]
Let us break down programming languages. See what is making the case
for a good language.
@snapend

@ul[mt20 size-80]
- @color[blue](Crash free), no blue screen, no freeze, no reboot.
- @color[blue](Performance), one step ahead of every human reaction.
- @color[blue](Strong type system), to tame complexity.
- @color[blue](Expressive), for us, between us.
- @color[blue](Predictable), there shall be no surprises.
- @color[blue](Productive), from prototype to production before the attention is lost.
@ulend

+++

The programer
=============

Being a programer, becoming a programer:

@ul
- Ripping apart @color[blue](problems), its related problems and problem within problems.
- Dividing them into @color[blue](smallest possible pieces).
- Until nothing is left but the @color[blue](atomic parts) of each one of them, @color[fragment](all of them).
- Repeat this again and again.
@ulend

@snap[mt20 text-gray text-center fragment]
Good luck, let us go back !
@snapend

---

Crash free
==========

---

Performance
===========

---

Strong type system
==================

---

Expressive
==========

---

Predictable
===========

---

Productive
==========

---

Why Rust ?
==========

<table>
<tr><th> Doing what    </th> <th> Rust     </th> <th> C        </th> <th> Python   </th> <th> Java     </th> <th> Golang   </th> <th> C#       </th> <th> Swift    </th> <th> js       </th> </tr>
<tr><td> Boot loader   </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> </tr>
<tr><td> Firmware      </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> </tr>
<tr><td> Kernel        </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> </tr>
<tr><td> Script        </td> <td> &#10004; </td> <td>          </td> <td> &#10004; </td> <td>          </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td> &#10004; </td> </tr>
<tr><td> Middleware    </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> </tr>
<tr><td> Algorithms    </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> </tr>
<tr><td> Database      </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td> &#10004; </td> <td>          </td> </tr>
<tr><td> Web-stack     </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> </tr>
<tr><td> Browser       </td> <td> &#10004; </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> <td>          </td> <td> &#10004; </td> </tr>
<tr><td> Windows       </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td> &#10004; </td> </tr>
<tr><td> OSX           </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td> &#10004; </td> <td> &#10004; </td> </tr>
<tr><td> Android / iOS </td> <td> &#10004; </td> <td>          </td> <td>          </td> <td> &#10004; </td> <td> &#10004; </td> <td>          </td> <td> &#10004; </td> <td>          </td> </tr>
</table>

In case of Rust some of the capabilities are work in progress, but are very much possible.

---

Rust and C
==========

Rust happens to carry forward all the goodness of C and avoiding,
as much as possible, its pitfalls, corner-cases and legacy issues.
Unlike C++'s large collection of features that stick out, Rust maintains
the C like philosophy through and through, to enable programmers with
small, but powerful set of features that can inter-play with each
other seamlessly.

<style> table th, table td { text-align: center !important; } </style>

<table class="south-west">
  <tr class="fragment">
    <th style="color: blue;"> Feature </th> <th> C </th> <th> Rust </th>
  </tr>
  <tr class="fragment">
    <td> Hardware access </td> <td class="text-blue"> Y </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Pointers </td> <td class="text-blue"> Y </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Link with C binary </td> <td class="text-blue"> Y </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Garbage collection </td> <td class="text-red"> N </td> <td class="text-red"> N </td>
  </tr>
  <tr class="fragment">
    <td> Zero Cost Abstraction </td> <td class="text-blue"> Y </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> LLVM Backend </td> <td class="text-blue"> Y </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Standard Library </td> <td class="text-blue"> Y </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Memory safety </td> <td class="text-red"> N </td> <td class="text-blue"> Y </td>
  </tr>
</table>

<table class="south-east">
  <tr class="fragment">
    <th style="color: blue;"> Feature </th> <th> C </th> <th> Rust </th>
  </tr>
  <tr class="fragment">
    <td> Type inference </td> <td class="text-red"> N </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Parametric types </td> <td class="text-red"> N </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Mono-morphisation </td> <td class="text-red"> N </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Enumerated types </td> <td class="text-red"> N </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Pattern matching </td> <td class="text-red"> N </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Build and packaging </td> <td class="text-red"> N </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Macro </td> <td class="text-red"> N </td> <td class="text-blue"> Y </td>
  </tr>
  <tr class="fragment">
    <td> Closures </td> <td class="text-red"> N </td> <td class="text-blue"> Y </td>
  </tr>
</table>

---

Rust language
=============

- Gives full control over memory and execution behaviour, similar to C/C++
- No Garbage-Collection, but guaranteed safety.
- No dangling pointers, no double free.
- Fearless concurrency, no data-races.

---

