# nocodb


[alembic]
script_location = alembic
prepend_sys_path = src
sqlalchemy.url = postgresql://postgres:postgres@localhost:5432/cc

[loggers]
keys = root,sqlalchemy,alembic

keys = root,sqlalchemy,alembic

keys = root,sqlalchemy,alembic

[handlers]
keys = console
dasdadasdas


[handler_console]
class = StreamHandler
args = (sys.stderr,)
level = NOTSET
formatter = generic

[formatter_generic]
format = %(levelname)-5.5s [%(name)s] %(message)s
datefmt = %H:%M:%S

