# Django <img src="http://www.mattmakai.com/source/static/img/presentations/2014-full-stack-python/django.png"  width="50"  />

24/09/2019

- **Site de dividas publicas em IA:** <a href="https://serenata.ai/">Serenata</a>
- **Site para digitar coisas aleatorias:** <a href="http://dontpad.com/">Dontpad</a>
- **Variavel deve ser criada assim:** `primeira letra sempre grande. Exemplo: Paçoca`
- **Iniciar venv ou env:** `python3 -m venv .venv`
- **Instalar requirements:** `pip install -r requirements.txt`
- **Ativar venv:** `source .venv/bin/activate`
- **Ver se está instalado o venv:** `python3 -m venv .venv`
- **Rodar server:** `python3 manage.py runserver`
- **CharField Null:** `null=True colocar o formulario como não obrigadotio`
- **Criar um makemagrations antes do migrate, gerar a tabela, logo após mudar a base:** `python3 manage.py makemigrations`
- **Migrar uma tabela para ter um banco de dados:** `python3 manage.py migrate`
- **Models:** 
`class Paçoca(models.Model): 
tipo =
cor = `
- **Documentação das Models:** <a href="https://docs.djangoproject.com/en/2.2/topics/db/models/">Documentation</a>
- **Models CharField para nome:** `models.CharField(max_lenght=255, verbose_name = 'nome')`

## Linux Terminal 

- **Após instalar itens:** - `sudo apt-get update` - `sudo apt-get upgrade`
- **Para instalar itens:** - `sudo apt-get install item` 
