## Instando e configurando Django

Django é um fremework para python que permite criar aplicações webs com arquitetura MVC. 

Para instalar o Django, basta digitar o comando no terminal (Linux/Mac): pip install django. Porém o Django será instalado em todo seu Sistema Operacional. Desse modo, existe uma forma de instalá-lo somente no ambiente onde vamos trabalhar, utilizando venv. Uma venv é um ambiente virtual para Python, que isola e fornece todas as condições para rodas aplicações Python. Para instalá-la, digita o comando no seu terminal:
```
> python3 -m venv ./venv
```
A documentação do venv pode ser encontrada em https://docs.python.org/3/library/venv.html. Caso tenha dificuldade para instalar venv, devido algum problema de bilbioteca, pode utilizar antes um gerenciador de pacotes, como conda, encontrado em https://docs.conda.io/en/latest/miniconda.html.
- Instalar Django: pip install django
- Criar projeto: python3 manage.py startproject
- Criar app: python3 manage.py startapp receitas
- Registrar em alurareceita/settings.py/INSTALLED_APPS = ['receitas']
-  


You can use the [editor on GitHub](https://github.com/charlyBraga/Django-receitas/edit/main/docs/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/charlyBraga/Django-receitas/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
