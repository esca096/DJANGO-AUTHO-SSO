# DJANGO-AUTHO-SSO

Ce projet Django permet a une application django d'interagir avec les reseaux sociaux comme google, facebook ou github pour ce connecter rapidement

# On aura besion d'intaller beaucoup de librairie comme:

- **pip install django-allauth**
- **pip install requests**
- **pip install PyJWT**
- **pip install cryptography**
- **pip install requests_oauthlib**


# On aura besion de crispy forms pour l'agencement du formulaire, pour cela on utiliser bootstrap 5 en installant:

- **pip install django-crispy-forms crispy-bootstrap5**
 on aura a ajouter ces codes dans les APPS django

    - **'crispy_forms',**
    - **'crispy_bootstrap5',**
  
  suivi de:
  
   Configuration de Crispy Forms
- **CRISPY_ALLOWED_TEMPLATE_PACKS = "bootstrap5"**
- **CRISPY_TEMPLATE_PACK = "bootstrap5"**

dans le settings.py

on fera un **pip freeze > requirements.txt** pour sauvegarder ces fichiers dans le requirements mains si on telecharge repo git alors on fera **pip install -r requirements.txt**

le tout dans un **environnement virtuel**
