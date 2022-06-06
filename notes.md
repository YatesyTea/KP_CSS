# Conquering Responsive Layouts Notes

# Day 1

> 

# Day 2

> rem vs em
> 
> * em adapts to text size and keeps things in proportion to text of the element.
> 
> * rem is in proportion to the default text size with 16px == 1 rem (references back to root text size).
>
> * Use rem for text sizes as em compounds with each element which can lead to really silly looking pages.
>
> * Use em for padding of child elements; references font size of current element, not that of the parent.
>
> * Use em when you want stuff to change with text size of element, use rem when you want stuff to stay consistent size no matter the size of element.

# Day 3

> Limiting Sizes
>
> * Instead of setting a width (which causes side scrolling), you can apply a max-width property (in px, or rem).
>

# Day 4
> CSS Units
>
> * vh and vw --> Viewport height and width respectively, are relative to viewport regardless of parent elements.
>
> * vmin and vmax --> whichever is smallest or biggest out of the vh and vw respectively is used for scaling.
>
> * Titles can use vh, vw, and vmin to be responsive.
>

# Day 5
