## Examples

Here is a gallery with various admonitions.
They should show up correctly on the built documentation too!

> [!tip]
> This is normally formatted. Type in lower case. No extra spaces.
> It contains two lines in markdown, but only a soft linebreak.

>   [!CAUTION]    
> This admonition has:  
> 
>   - ALL CAPS in the type
>   - a list
> 
> Note that this admonition uses the "danger" symbol with "Caution" title.

> [!Important]
> This contains `inline` and
> ```python
> import this  # python code in ticks
> ```
>
>     and code block with spaces
>
> Note that this admonition uses the "warning" symbol with "Important" title.

> [!note]
> And this admonition contains an empty line
>
> That only has a `>` character in markdown.

> [!warning]
> Admonitions may contains quotes
> > Quotes always contain great wisdom. 

But pay attention! There may be admonitions which are really just code:
```text
> [!note]
> This is not an admonition.