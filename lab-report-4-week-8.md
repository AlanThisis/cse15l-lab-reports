# Lab Report 4

## Markdown-Parse Repositories

My repository is [here.](https://github.com/AlanThisis/markdown-parse)

The repository that I reviewed is [here.](https://github.com/merrickqiu/markdown-parse)

## Snippet Tests
---
### Snippet 1 

* MarkdownParse should produce an ArrayList like the following for snippet 1:

```
["`google.com","google.com","ucsd.edu"]
```
* MarkdownParse should produce an ArrayList like the following for snippet 2:

```
["a.com","a.com(())","example.com"]
```
* MarkdownParse should produce an ArrayList like the following for snippet 3:

```
["https://ucsd-cse15l-w22.github.io/"]
```

## Junit Test Implementation
---
The following code is in MarkdownParseTest.java of my repo and the repo I reviewed:

![image](screenshots4/junit-test-snippets.png)

* LinksTester is the expected output of MarkdownParse
* fileName contains the markdown file name
* links is the actual output of MarkdownParse getLinks method

## Outputs of Junit Test
---
### **my repo**
* the output of my repo:

![image](screenshots4/my-repo-output.png)

* None of the snippet tests are passed.

### **review repo**
* the output of the reviewed repo:

![image](screenshots4/review-repo-output.png)

* None of the snippet tests are passed.
