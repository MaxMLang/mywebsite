---
title: Wilson's Theorem (Proof)
author: Max Lang
date: '2021-01-01'
slug: wilson-s-theorem-proof
categories:
  - Mathematics
  - Proof
tags: []
---
# Proof

Wilson's theorem states:

Let *p* be a prime. Then

`$ (p - 1)! \equiv -1 \quad mod \;p $`

`$ \text{Each a}  \{1 , 2, ..., p - 1 \} \text{has a inverse } a^{-1} \in \{ 1 , 2, ..., p - 1 \} \; mod \;p \text{ with } a \cdot a^{-1} = 1 \text{.} $`

`$ \text{This inverse } a^{-1} \text{ is unique and via the power laws follows that } {a^{-1}}^{-1} = a \; (mod\;p)\text{. In addition If } a=a^{-1} \text{ then } 1 \equiv a\cdot a^{-1} = a^2. \text{ This necessitates } a \equiv \pm 1 \text{ and therefore } a= 1 \; ; (a=p-1 \; mod \; p) $`

`$ \text{In the product} (p-1)!= 1\times2\times3\times4\times\ldots\times (p-2)\times (p-1) \text{each term except for 1 and } (p-1) \text{paired with its inverse modulo } p \text{ is equal to } 1 \text{. Because of the inverse property } a\cdot a^{-1}=1, \text{ we thus get} (p-1)! \equiv 1\times (p-1) \equiv -1 \; mod \;p \quad q.e.d $`
`$ \text{This is possible because in the rest classes } [x]_p \text{ the only self inverse elements are } x=1=x^{-1} \text{ and } (p-1)$`

`$ \text{As an illustration have a look at the table of operations of } \mathbb (Z_5, \times) $`

| $\times$ | 1 | 2 | 3 | 4 |
|----------|---|---|---|---|
|1|1|2|3|4|
|2|2|4|1|3|
|3|3|1|4|2|
|4|4|3|2|1|

`$ \text{As you can see the only elements} \text{ for which } a^2=1  \text{ are } a = 1 \text{ and } b = 4.$`



# Thoughts
I had to proof this theorem in my Linear Algebra class and it took me a couple of hours to figure it out, especially baceause at first sight I did not believe that this could actually be true. I think the best way is to use an example like $\mathbb Z_5$. 

After the work it was a pretty cool proof in my opinion. Even though the Theorem's practical usage is limited, it is still useful to find out Remainders of super large numbers in a second.
