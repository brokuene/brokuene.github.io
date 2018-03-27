---
layout: post
title: First post
date: 2018-03-25 20:18:03
tags: [js, c#]
---

#### This is a first post ####
This will be a first post. We will see how it looks like to have a blog or website on 'Github pages'.
I am a little bit sceptical but we will see :confused::pensive:...

Lets try a code here:
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
Some code with C#:
```csharp
for (int i = 0 ; i < 10; i++)
{
// Code to execute.
}
```
And some code without C#
```
for (int i = 0 ; i < 10; i++)
{
// Code to execute.
}
```
This one will be some strange syntax highlight attempt
{{ "{% highlight javascript " }}%}  
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{{ "{% endhighlight " }}%} 

Here inline code `code(run).fast().then().quit();`

The very long block of code would look like below for C#:
```csharp
/*
 * C# Program to Check whether the Entered Number is Even or Odd
 */
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
 
namespace check1
{
    class Program
    {
        static void Main(string[] args)
        {
            int i;
            Console.Write("Enter a Number : ");
            i = int.Parse(Console.ReadLine());
            if (i % 2 == 0)
            {
                Console.Write("Entered Number is an Even Number");
                Console.Read();
            }
            else
            {
                Console.Write("Entered Number is an Odd Number");
                Console.Read();
            }
        }
    }
    
    class Program2
    {
        void Main2(string[] args)
        {
            int i;
            Console.Write("Enter a Number : ");
            i = int.Parse(Console.ReadLine());
            if (i % 2 == 0)
            {
                Console.Write("Entered Number is an Even Number");
                Console.Read();
            }
            else
            {
                Console.Write("Entered Number is an Odd Number");
                Console.Read();
            }
        }
    }
}
```
