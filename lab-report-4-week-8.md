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

## Code Changes for Snippet Tests
---

### Snippet 1

For Snippet 1, I think a small code change for getting links with inline ocde with back ticks is possible. 

**code change**
> Add an instance that contains the index of back tick. The instance should check for the indices of back ticks of each line. Under certain conditions the getLink method would return a link. 
>1) not enclosing back ticks
    >>* return the link unless the back tick is in between the closing bracket and the openning parenthesis
>2) enclosing back ticks - the following are conditions when a link should be returned
    >>* both back ticks are within the brackets
    >>* both back ticks are within the parentheses
    >>* first back tick is in the parenthesis, and second parenthesis is after closing parenthesis

### Snippet 2




