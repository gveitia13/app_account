# app_account
### urls.py 

path('accounts/', include('app_account.urls')),

### settings.py

INSTALLED_APPS = [

    ...
    'app_account',
    ...
]

#### Adaptar las variables al contexto de tu proyecto

