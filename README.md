We communicate programming techniques in many informal and semi-structured modes of communication: conversation, presentation, web applications such as Stack Overflow, lecture notes, and so on. The purpose of this repository is to experiment with semi-structured formats for conveying the craft of programming, formats that allow us to use tools such as diff and PRs.

How to use this repository
--------------------------
Examine the example directory, distributed-computing-at-scale. It contains programming techniques documented in three forms. First, an excerpt from a source narrative describing the venerable craft of "printf debugging""

![printf debugging on a slide](https://github.com/SamPenrose/decision-tree-coding/raw/master/narrative-example.png "Advice on slide")

Then a markdown-style specification in Graphviz's dot language (excerpted):

```
    "Start with working code" -> "Make a small edit"
    "Make a small edit" -> "Run program"
    "Run program" -> "Observe behavior"
    "Observe behavior" -> "Is behavior expected?"
    "Is behavior expected?" -> "Make a small edit"[label="Yes"]
    "Is behavior expected?" -> "to \"Print debugging\""[label="No"]
```

and finally, the specification compiled to a flowchart:

![Flowchart](https://github.com/SamPenrose/decision-tree-coding/raw/master/distributed-computing-at-scale/svg/normal.svg "Flowchart")

Which form conveys the technique most clearly?

File issues and PRs
-------------------
Please express your reactions to these examples in opened issues and PRs.

TODO
----
* Test formats for effectiveness in transfering knowledge
* Specify more techniques
* Experiment with formats such as mermaid that generate rich HTML.
* Explore integration with Jupyter notebooks
* Lots more!