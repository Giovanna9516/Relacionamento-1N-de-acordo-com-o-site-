# Relacionamento-1N-de-acordo-com-o-site-

class Evento(models.Model):
    atividade = models.ForeignKey("Atividade", on_delete=models.CASCADE, related_name='evento')

python manage.py makemigrations

python manage.py migrate 

(#comentario#) mas no site fala de banco de dados, então ja não sei)

# Relacionamento NN

from django.db import models

#tem nada haver fica faltando muita coisa 
