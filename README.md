# Ecn. IS LM model interactive document
*ecn-is-lm*

**What is it?**

A project containing an interactive IS-LM model graph https://tmiranda-ecn-is-lm.netlify.com/

---

 - Veja o link acima para acessar o trabalho exportado em HTML contendo o gráfico interativo
 - Acesse `index.org` para ver e contribuir para o documento em [org-babel](https://orgmode.org/worg/org-contrib/babel/)
 - Acesse o [codepen](https://codepen.io/TCMiranda/pen/bKJaMV?editors=1010) para visualizar e contribuir com o código do gráfico interativo
 
 Tema inspirado no estilo de https://readthedocs.org readaptado de https://github.com/fniessen/org-html-themes
 
### Contribution

O código do projeto foi desenvolvido em Org usando Emacs.

Para executar será necessário (para emacs) os pacotes instalados:
  - org-mode
  - ob-mermaid
  - ob-restclient
  
E a seguinte configuração do .emacs
```
(org-babel-do-load-languages 'org-babel-load-languages '
  ((js . t)
   (mermaid . t)
   (octave . t)
  ))
```
 
O resultado pode ser visualizado exportando para html o arquivo `index.org`
