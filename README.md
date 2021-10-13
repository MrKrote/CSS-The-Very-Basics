# CSS-The-Very-Basics

>  
> CSS: The Very Basics (Cascading Style Sheets)
>

**What is CSS?**

- CSS is a language for describing how documents are presented visually.

**CSS Rules**

Almost everything you do in CSS follows this basic pattern:

```
selector {
    property: value;
}
```

**Pl.:**

Make all ```<h1>``` elements purple
  
```
h1 {
    color: purple;
}
```

**CSS Reference**

**Website** : https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

&nbsp;

>  
> CSS: The Very Basics (Cascading Style Sheets)
> Including Styles

Write your styles in a ```.css``` file and then include the using a ```<link>``` in the head of your HTML document.

**The ```<link>``` file**

```
<head>
    <title> Forms Demo </title>
    <link rel="stylesheet" href="FormsDemoStyle.css">
</head>
```

&nbsp;

>  
> CSS: The Very Basics (Cascading Style Sheets)
> Color Systems:

**Names**

Website: https://htmlcolorcodes.com/color-names/



**RGB** - ```rgb(0,0,0)```

Website: https://htmlcolorcodes.com/color-picker/



**Hexadecimal** - ```#ffff00```

0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F

```#```  ```ff``` - red (255)
```ff``` - green(255)
```00``` - blue


Hexadecimal can be short: 

```#000000``` - its black ->```#000```

```#cc55ee``` - its pink ->```#c5e```

Website: https://htmlcolorcodes.com/color-picker/

&nbsp;

>  
> CSS: The Very Basics (Cascading Style Sheets)
> 
> Common Text Properties

**1.** ```text-align:```  ```center;``` | ```left;``` | ```right;``` - they're all aligned to the right of their respective sort of content boxes.

**2.** ```font-weight:``` ```400;``` | ```normal;``` | ```bold;```

**3.** ```text-decoration:``` ```#f88945 underline dotted;``` | ```underline wavy;```

**4.** ```line-height:``` ```2;``` | ```normal```

**5.** ```letter-spacing:``` ```7px;```

**6.**  ```font-size:``` ```80px;```

**7.**  ```font-family:``` ```Verdana, Futura, Arial;``` - Verdana is the first one the anothers are backup 

Website - https://www.cssfontstack.com/
