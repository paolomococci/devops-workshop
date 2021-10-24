# postgresql_django

## commands used

```text
docker-compose run -h
docker-compose run web django-admin startproject project_files .
sudo chown -R $USER:$USER .
```

## edit project_files/settings.py

```text
DATABASES = {
    'default': {
        #'ENGINE': 'django.db.backends.sqlite3',
        #'NAME': BASE_DIR / 'db.sqlite3',
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'postgres',
        'USER': 'postgres',
        'PASSWORD': 'postgres',
        'HOST': 'db',
        'PORT': 5432,
    }
}
```

## to follow, other commands used

```text
docker-compose up -d
docker-compose ps
docker ps --all
docker volume ls
docker-compose down
```
