start
:Ingresar nombre de usuario y contraseña;
:Validar nombre de usuario;
if (¿Nombre de usuario válido?) then (sí)
  :Validar contraseña;
  if (¿Contraseña válida?) then (sí)
    :Acceder al sistema;
    stop
  else (no)
    :Mostrar error de contraseña;
    :Volver a intentar;
    stop
  endif
else (no)
  :Mostrar error de usuario;
  :Volver a intentar;
  stop
