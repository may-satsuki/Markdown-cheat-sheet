<!-- 
Name: Markdown Cheet Sheet
author: may-satsuki (https://github.com/may-satsuki)
-->


<!-- Header -->
# Header

# Header Lv.1
## Header Lv.2
### Header Lv.3
#### Header Lv.4
##### Header Lv.5
######　Header Lv.6

【Source】
```markdown
# Header Lv.1
## Header Lv.2
### Header Lv.3
#### Header Lv.4
##### Header Lv.5
######　Header Lv.6
```
<br><br>

<!-- Text Decoration -->
# Text Decoration
*italic*<br>
_italic_<br>
**bold**<br>
__bold__


【Source】
```markdown
*italic*<br>
_italic_<br>
**bold**<br>
__bold__
```
<br>

<!-- List -->
# List

## List
* item
+ item
- item

1. item1
2. item2
3. item3

【Source】
```markdown
* item
+ item
- item

1. item1
2. item2
3. item3
```

## Nest List
- List1
  - Nest List1_1
     - Nest List1_1_1
     - Nest List1_1_2
  - Nest List1_2
- List2
- List3

【Source】
```markdown
- List1
  - Nest List1_1
     - Nest List1_1_1
     - Nest List1_1_2
  - Nest List1_2
- List2
- List3
```
<br><br>

<!-- Quote -->
# Quote
> Quote<br>
> Quote<br> 
>> Include Quote II
>>> Incruded Quote III

【Source】
```markdown
> Quote<br>
> Quote<br> 
>> Include Quote II
>>> Incruded Quote III
```
<br><br>


<!-- Table -->
# Table
| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |


【Source】
```markdown
| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |
```
<br><br>


<!-- Line -->
# Line
---
***
* * *

【Source】
```markdown
---
***
* * *
```
<br><br>


<!-- Link -->
# Link
[GitHub](https://github.com/)<br>
[Google](https://www.google.com/)

【Source】
```markdown
[GitHub](https://github.com/)<br>
[Google](https://www.google.com/)
```
<br><br>


<!-- Strike -->
#Strike

~~Strike~~

【Source】
```markdown
~~Strike~~
```
<br><br>

<!-- Insert Image -->
Form Web<br>
![Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg
 "Markdown")
<br><br>
Inline SVG Image<br>
<svg xmlns="http://www.w3.org/2000/svg" width="208" height="128" viewBox="0 0 208 128"><rect width="198" height="118" x="5" y="5" ry="10" stroke="#999" stroke-width="10" fill="none"/><path d="M30 98V30h20l20 25 20-25h20v68H90V59L70 84 50 59v39zm125 0l-30-33h20V30h20v35h20z"/></svg>
<br>

<!-- Eqortipn -->

```math
\left( \sum_{k=1}^n a_k b_k \right)^{!!2} \leq
\left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
$a = \\{1, 2, 3\\}$
```

<!-- Inline Source -->
【C cource】
```c
#include <stdio.h>
int main(int argc, char *argv[])
{
    printf("hello, world!\n");
}
```

```math
e^{i\pi} = -1
```
