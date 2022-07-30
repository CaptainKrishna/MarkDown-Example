# MarkDown Markup Languge  
## Heading  
```md

# Heading 1

## Heading 2  
  
### Heading 3  

#### Heading 4  

##### Heading 5  

###### Heading 6  
```
## Comments  
```md
<!--  
 //Code
 -->  
```
___
## For Next Line
> Using Double space in ending__ 
```md
this is line 1__  
this is line 2

or 

<br/>
``` 
this is line 1  
this is line 2

or   

this is line 1<br/>
this is line 2 
___
## For Horizontal Line
> Using triple ___
```md
___

or

<hr/>

``` 
>.
> ___
>.  
>.
><hr/>
>.
___
## For Next Line
> Using Double space in ending__ 

___
## Paragraph  
```md  
</br>
```  
___
## Lists  
### Order List
```md  
We can use (1,2,3)

 1.list
 2.list
 3.List  

```

### Unorder List
```md  
We can use any of these ( * , + , - )

 *list
 +list
 -List  

```
### Nested List
```md  
We can use (1,2,3) & ( - , + , * )

Order List
 
 1.list
   -item1
   -item2
   -item3  

Unorder List
 
 -list
    1.item1
    2.item2
    3.item3

```

___  
## Link
```md  
[Click here](https://www.google.com)
```
[Click here](https://www.google.com)

___  
## Image
```md  
![Example Image](/Image.png)
```
![Example Image](/image.png)

___  
## Link And Image
```md  
[![Example Image](/Google.png)](https://www.google.com)
```
[![Example Image](/Google.png)](https://www.google.com)

___
## Block of Code
```md  
> This is block Code
```
> This is block Code
```md  
> space between Block code
>                   
> This is block Code
```
> space between Block code
> 
> This is block Code

```md  
> This is List of Block
> 1.Item1                  
> 2.Item2                  
> 3.Item3                  
```
> This is List of Block  
> 1.Item1                  
> 2.Item2                  
> 3.Item3  
```md  
> Block under Sub Block    
>> 1.Item1                  
>> 2.Item2                  
>> 3.Item3                  
```
> Block under Sub Block  
>>1.Item1                  
> 2.Item2                  
> 3.Item3  
___
  
  ## Tables  

```md
|    FirstName   |   LastName   |  
| :------------: |  :----------:|  
|    Krishna     |  Vishwakarma |  
|    Krishna 2   |  Vishwakarma |  
|    Krishna 3   |  Vishwakarma |  

```
|    FirstName   |   LastName   |  
|:--------------:|:------------:|  
|    Krishna     |  Vishwakarma |  
|    Krishna 2   |  Vishwakarma |  
|    Krishna 3   |  Vishwakarma |  
___

## How To Convert MarkDown To Html</br>
  
>Open terminal in same folder
### Step 1

> npm install -g markdown-it  

### Step 2

> markdown-it readme.md -o readme.html

