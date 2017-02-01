---
layout: post
title:  "C tutorial 6:Loops"
date:   2017-02-01 07:37:33
categories: c-tutorial
---
`loops` you will find many loops on other programs if you watch any, now how to apply `loops`, there are three methods, the `while loop`, `the do while loop`, the `for loop`. Now lets see how they are used and why<br>
while(comdition){<br>
  statements;
}
`while` loop will looks for condition, if condition is true, then it will run until the condition gets false.<br>
do(condition){<br>
  statements;
}
'do while' loop is similar to while loop, the only difference is that, in `do while` loop the loop runs for once then it checks for the condition.<br>
for(initialization;condition;updation)
{
  statements;
}
`for`loop is the most used loop, and as easy to understand as other loops.<br>
Lets print a number twice using for loop

[% highlight ruby %]
int a;
scanf("%d",&a);
for(int i=0;i<2;i++)
{
  printf("%d/n",a);
}
{% endhighlight %}
for input a=10<br>
Output:
<blockquote>
10
10
10
</blockquote>

