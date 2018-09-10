#Markdown with code example

Github has built-in Markdown viewers, too.

For example, you can write a code block like this:

```
#This is R code embedded in a Markdown file
x<-rnorm(1000);
y<-rnorm(1000);
plot(x,y);

What will the output of this be?
```

##Normal distributions in R

The function R norm will sample data from a normal distributions.  So, the call, rnorm(1000) will sample 1000 values from a normal distribtion with mean 0 and standard deviation 1.