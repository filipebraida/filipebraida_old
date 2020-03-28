---
layout: post
title: Hello Word!
---

Esse primeiro post será um guia de referência para a utilização das funcionalidades do blog.

## Funcionalidades

### Listas:

É possível criar enumerados:
- Valor 1
- Valor 2
- Valor 3

### LaTeX:

É possível adicionar formulas utilizando a sintaxe do LaTeX.

Exemplo:
> When $$ 
a \ne 0 $$, there are two solutions to $$ ax^2 + bx + c = 0 $$ and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

### Código:

Uma funcionalidade importante será a utilização de pedaços de códigos para ilustrar alguns exemplos. Será um grande artifício, principalmente, para computação científica.

- Código em Python  

```python
def function():
  print('Yes')
```

- Código em Julia:

```julia
function sphere_vol(r)
    # julia allows Unicode names (in UTF-8 encoding)
    # so either "pi" or the symbol π can be used
    return 4/3*pi*r^3
end
```

- Clássico C:
  
```c
int main(void) {
    printf("Hello World\n");
    return 0;
}
```