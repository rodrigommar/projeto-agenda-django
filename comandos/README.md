# inciar o projeto Django
python -m venv venv
. venv/scripts/activate
pip install django
django-admin startproject project
python manage.py startapp contact


# configurando github
git config --global user.name 'Rodrigo Mar'
git config --global user.email 'rodrigommar@gmail.com'
git config --global init.defaultBranch main
# configure o .gitignore
git init
git add .
git commit -m 'mensagem'
git push origin main -u (O parametro -u é apenas na primeira vez)
git log
git log --oneline
git remote add origin URL_diretorio_do_github