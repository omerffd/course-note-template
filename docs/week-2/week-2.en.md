---
marp: true
theme: default
style: |
    img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Sample Course Name'
footer: '![height:50px](http://erdogan.edu.tr/Images/Uploads/MyContents/L_379-20170718142719217230.jpg) RTEU CE204 Week-2'
title: "Sample Course Name"
author: "Author: Asst. Prof. Dr. Uğur CORUH"
date:
subtitle: "Sample Course Module Name"
geometry: "left=2.54cm,right=2.54cm,top=1.91cm,bottom=1.91cm"
titlepage: true
titlepage-color: "FFFFFF"
titlepage-text-color: "000000"
titlepage-rule-color: "CCCCCC"
titlepage-rule-height: 4
logo: "assets/2021-10-19-15-01-36-image.png"
logo-width: 100 
page-background:
page-background-opacity:
links-as-notes: true
lot: true
lof: true
listings-disable-line-numbers: true
listings-no-page-break: false
disable-header-and-footer: false
header-left:
header-center:
header-right:
footer-left: "© Asst. Prof. Dr. Uğur CORUH"
footer-center: "License: WTFPL"
footer-right:
subparagraph: true
lang: en-US 

math: katex
---

<!-- _backgroundColor: aquq -->

<!-- _color: orange -->

<!-- paginate: false -->

## Sample Course Name

### Week-2 (Sample Course Module Name)

#### Spring Semester, 20XX-20XX

Download [DOC](week-2.en.md_doc.pdf), [SLIDE](week-2.en.md_slide.pdf), [PPTX](week-2.en.md_slide.pptx)

<iframe width=700, height=500 frameBorder=0 src="../week-2.en.md_slide.html"></iframe>

---

<!-- paginate: true -->

### Outline

- Flowgorithm

---

## **What is Flowgorithm ?**

---

### Sample Topic

- ****What is Flowgorithm ?****
  **Flowgorithm** is a graphical [authoring tool](https://en.wikipedia.org/wiki/Authoring_tool "Authoring tool") which allows users to write and execute programs using [flowcharts](https://en.wikipedia.org/wiki/Flowchart "Flowchart"). The approach is designed to emphasize the algorithm rather than the syntax of a specific programming language.The flowchart can be converted to several major programming languages. Flowgorithm was created at [Sacramento State University](https://en.wikipedia.org/wiki/Sacramento_State_University "Sacramento State University").

---

### Sample Images-1

- ****What is Flowgorithm?****
  Flowgorithm is a **free** beginner's programming language that is based on simple graphical flowcharts.
  
  Typically, when a student first learns to program, they often use one of the text-based programming languages. Depending on the language, this can either be easy or frustratingly difficult. Many languages require you to write lines of confusing code just to display the text "Hello, world!".
  
  By using flowcharts, you can concentrate on programming concepts rather than all the nuances of a typical programming language. You can also run your programs directly in Flowgorithm.
  
  Once you understand programming logic, it is easy for you to learn one of the major languages. Flowgorithm can interactively convert your flowchart to over 18 languages. These include: C#, C++, Java, JavaScript, Lua, Perl, Python, Ruby, Swift, Visual Basic .NET, and VBA (used in Office).



---

### Sample Images-2

- ****What is Flowgorithm?****
  Flowgorithm is a graphical authoring tool which allows users to write and execute programs using flowcharts. The approach is designed to emphasize the algorithm rather than the syntax of a specific programming language.The flowchart can be converted to several major programming languages. Flowgorithm was created at Sacramento State University.



---

### Sample Images-3

- ![Flowgorithm Tutorial - TestingDocs.com](https://www.testingdocs.com/wp-content/uploads/flowgorithm-logo.png)

---

### Sample Images-4

- **How is download Flowgorithm ?**
  [http://www.flowgorithm.org/](http://www.flowgorithm.org/)

---

### Sample Images-5

- **What does Flowgorithm do?**
  Flowgorithm is a graphical authoring tool which **allows users to write and execute programs using flowcharts**. The approach is designed to emphasize the algorithm rather than the syntax of a specific programming language. The flowchart can be converted to several major programming languages.

)![Flowgorithm - Wikipedia](https://upload.wikimedia.org/wikipedia/commons/4/42/Flowgorithm_99_Bottles_of_Beer.png)

---

# 

---

### Latex Sample-1

$$
\begin{align}
  \begin{aligned}
  \text{compute } m[i,i+1] \\
  \underbrace{ \{ m[1,2],m[2,3], \dots ,m[n-1,n]\} }_{(n-1) \text{ values}}
  \end{aligned}
    & \begin{cases}
    & \ell=2  \\
    & \text{for } i=1 \text{ to } n-1 \text{ do } \\
    & \quad m[i,i+1]=\infty \\
    & \quad \quad \text{for } k=i \text{ to } i \text{ do } \\
    &  \quad \quad \quad \vdots
    \end{cases} \\
  \begin{aligned}
  \text{compute } m[i,i+2] \\
  \underbrace{ \{ m[1,3],m[2,4], \dots ,m[n-2,n]\} }_{(n-2) \text{ values}}
  \end{aligned}
    & \begin{cases}
    & \ell=3  \\
    & \text{for } i=1 \text{ to } n-2 \text{ do } \\
    & \quad m[i,i+2]=\infty \\
    & \quad \quad \text{for } k=i \text{ to } i+1 \text{ do } \\
    & \quad \quad \quad \vdots
    \end{cases} \\
  \begin{aligned}
  \text{compute } m[i,i+3] \\
  \underbrace{ \{ m[1,4],m[2,5], \dots ,m[n-3,n]\} }_{(n-3) \text{ values}}
    \end{aligned}
    & \begin{cases}
    & \ell=4  \\
    & \text{for } i=1 \text{ to } n-3 \text{ do } \\
    & \quad m[i,i+3]=\infty \\
    & \quad \quad \text{for } k=i \text{ to } i+2 \text{ do } \\
    & \quad \quad \quad \vdots
    \end{cases}
\end{align}
$$

---

### Latex Sample-2

$$
\begin{align*}
& \text{OPTIMAL-BST-COST} (p, n) \\
& \quad \text{for} \ i \leftarrow 1 \ \text{to} \ n \ \text{do} \\
& \qquad c[i, i-1] \leftarrow 0 \\
& \qquad c[i, i] \leftarrow p[i] \\
& \qquad R[i, j] \leftarrow i \\
& \quad PS[1] \leftarrow p[1] \Longleftarrow PS[i] \rightarrow  \text{ prefix-sum } (i): \text{Sum of all} \ p[j] \ \text{values for}  \ j \leq i
 \\
& \quad \text{for} \ i \leftarrow 2 \ \text{to} \ n \ \text{do} \\
& \qquad PS[i] \leftarrow p[i] + PS[i-1]  \Longleftarrow  \text{compute the prefix sum} \\
& \quad \text{for} \ d \leftarrow 1 \ \text{to} \ n−1 \ \text{do}   \Longleftarrow  \text{BSTs with} \ d+1 \ \text{consecutive keys} \\
& \qquad \text{for} \  i \leftarrow 1 \ \text{to} \ n – d \ \text{do} \\
& \qquad \quad j \leftarrow i + d \\
& \qquad \quad c[i, j] \leftarrow \infty \\
& \qquad \quad \text{for} \ r \leftarrow i \ \text{to} \ j \ \text{do} \\
& \qquad \qquad q \leftarrow min\{c[i,r-1] + c[r+1, j]\} +  PS[j] – PS[i-1]\} \\
& \qquad \qquad \text{if} \ q < c[i, j] \ \text{then} \\
& \qquad \qquad \quad c[i, j]  \leftarrow q \\
& \qquad \qquad \quad R[i, j] \leftarrow r \\
& \quad \text{return} \ c[1, n], R
\end{align*}
$$

---

**TODO** UPDATE CONTENT FOR YOUR COURSE NOTES

--- 

## References

- http://www.flowgorithm.org/
- [Flowgorithm - Wikipedia](https://en.wikipedia.org/wiki/Flowgorithm)
- [Flowgorithm - Wikiwand](https://www.wikiwand.com/en/Flowgorithm)
- https://upload.wikimedia.org/wikipedia/commons/4/42/Flowgorithm_99_Bottles_of_Beer.png
- https://www.testingdocs.com/wp-content/uploads/flowgorithm-logo.png

---

$End-Of-Week-2-Module$
