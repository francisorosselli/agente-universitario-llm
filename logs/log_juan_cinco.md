# Entrevista con Juan Cinco

##Conversación completa
```
BAIT: Hola, soy BAIT, el asistente académico de tu universidad.
 Mi misión es ayudarte a descubrir y conectar con otras personas que compartan tus intereses, ideas o sueños profesionales.
 Lo que me cuentes no será compartido directamente con nadie.
 Pero si encuentro coincidencias o complementariedad con otros perfiles, podré sugerir una conexión respetuosa, solo si vos estás de acuerdo.
 Podés terminar la entrevista en cualquier momento, escribiendo 'fin' o 'salir'.
¿Te gustaría contarme tu nombre, carrera y año para que pueda guardar tu perfil y ayudarte a conectar con otros?
Usuario: soy juan cinco, estoy en 5to año de administracion de empresas
BAIT: ¿Qué te motivó a estudiar administración de empresas y qué esperas lograr en tu carrera profesional?
Usuario: me encantó la materia de recursos humanos
```

##Perfil estructurado (JSON)
```json
{
  "nombre": "Juan Cinco",
  "carrera": "Administración de Empresas",
  "año": "5",
  "intereses_académicos": "Recursos Humanos",
  "idea_o_proyecto_actual": "",
  "sueño_u_objetivo_profesional": ""
}
```

##Resumen final para embeddings
```
es un estudiante de quinto año de _ con intereses académicos en Recursos Humanos. Actualmente no tiene una idea o proyecto en curso, pero su sueño u objetivo profesional no está especificado en su perfil.
```

##Conexiones sugeridas o mensaje de cierre
```
Estimado estudiante,

Fue un placer conversar contigo y conocer más sobre tus intereses y proyectos académicos. Aunque aún no encontramos coincidencias en nuestra base de datos, tu perfil es muy prometedor y creo que tenemos mucho potencial para colaborar juntos en el futuro.

Sigue trabajando duro y explorando nuevas oportunidades en tu camino académico y profesional. Estoy aquí para apoyarte en lo que necesites y para ayudarte a conectar con otros estudiantes y profesionales que compartan tus intereses.

¡No dudes en contactarme si necesitas orientación o si quieres seguir explorando posibles colaboraciones! Estoy aquí para ayudarte a alcanzar tus metas y construir una comunidad académica sólida.

¡Mucho éxito en tus futuros proyectos!

Saludos cordiales,
BAIT
```

