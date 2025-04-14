##Fetch SRE

##### How to run?
First time:

```
go init blah.com/blah
go mod tidy
```

Once libraries are mod and no other changes for libs:

```go run main.go <file-name>.yaml```


###Method to update
+ I just ran it and it gave me an ioutil error, I swapped the depcrecated ioutil with os.
+ Went through requirements and found things that already there, like it's already printing and testing, already waiting and sleeping for 15 seconds
+ I added a time check for each function run to check time now and see whenever duration is more than ms500 it should not be printed.

###Notes/FAQ
+ Did I use AI?
no

+ Am I a developer?
no

+ Did I develop a lot of solutions using go before?
Yes

+ How?
I know all the structure for go lang, specially for kube client and other main libraries, i use Copilot and/or watsonx ai assistant for main functionality. NOT the logic or anything else, still I understand all the code and I know how to find in docs what I am looking for.

### What are my strengths?

Kubernetes, OpenShift, Linux, Bash,Controllers, IoC , ArgoCD, ArgoWorkflow, AWS, AI/ML Agents ...etc