# Markdown fenced code issues

I am encountering some issues with the way Textastic for iOS is rendering Markdown previews. The [Textastic developer](http://twitter.com/textastic) has [said on the Textastic help forum](http://feedback.textasticapp.com/topic/83965-markdownmultimarkdown-to-html/) that he uses the [Discount Markdown renderer](http://www.pell.portland.or.us/~orc/Code/discount/), and that he compiles the library with the proper arguments to support fenced code blocks (and he confirmed this to me [on Twitter](http://twitter.com/Textastic/status/334861322061766656)), so perhaps this issue lies with that library. See below for some samples of Markdown that I'm seeing issues with, and a screenshot of the Markdown as it is rendered in Textastic for iOS.

## Functionality using backticks


    here is some space-indented code

    
```here is some backtick-fenced code w/ same-line backticks```



```
here is some backtick-fenced code w/ the code on its own line
```


```
here is a block of
backtick-fenced code
with some newlines
inside (umm...)
```


```
another block of backtick-fenced code

with doubled-up

newlines inside
```


---


## Functionality using tildes


~~~here is some tilde-fenced code w/ same-line tildes (curious...)~~~



~~~
here is some tilde-fenced code w/ the code on its own line
~~~


~~~
here is a block of
tilde-fenced code
with some newlines
inside (better!)
~~~


~~~
another block of tilde-fenced code

with doubled-up

newlines inside
~~~

---

## Screenshot of the above markdown as rendered by Textastic for iOS (iPad):

<img src="https://dl.dropboxusercontent.com/u/488478/IMG_0097.PNG"  />