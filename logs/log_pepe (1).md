# Entrevista con pepe

##Conversación completa
```
BAIT: Hola, soy BAIT, el asistente académico de tu universidad.
 Mi misión es ayudarte a descubrir y conectar con otras personas que compartan tus intereses, ideas o sueños profesionales.
 Lo que me cuentes no será compartido directamente con nadie.
 Pero si encuentro coincidencias o complementariedad con otros perfiles, podré sugerir una conexión respetuosa, solo si vos estás de acuerdo.
 Podés terminar la entrevista en cualquier momento, escribiendo 'fin' o 'salir'.
¿Te gustaría contarme tu nombre, carrera y año para que pueda guardar tu perfil y ayudarte a conectar con otros?
Usuario: soy pepe, estoy en 5to año de agronomia
BAIT: ¿Qué te motivó a estudiar agronomía y qué esperas lograr una vez que te gradúes?
Usuario: me apasiona la ganaderia, cuando me reciba quiero fundar el feedlot  mas grande del pais
BAIT: ¿Qué aspectos específicos de la ganadería te interesan más y cómo planeas aplicarlos en tu proyecto de fundar el feedlot más grande del país?
Usuario: me interesa la reproducion animal y la clonacion
```

##Perfil estructurado (JSON)
```json
{
  "nombre": "pepe",
  "carrera": "agronomía",
  "año": "5",
  "intereses_académicos": "reproducción animal, clonación",
  "idea_o_proyecto_actual": "Fundar el feedlot más grande del país",
  "sueño_u_objetivo_profesional": "Convertirse en el fundador y líder de un feedlot de renombre nacional"
}
```

##Resumen final para embeddings
```
Estudiante de quinto año de Agronomía con intereses académicos en reproducción animal y clonación. Actualmente trabaja en la idea de fundar el feedlot más grande del país, con el objetivo profesional de convertirse en el líder de un feedlot reconocido a nivel nacional.
```

##Conexiones sugeridas o mensaje de cierre
```
Estimado estudiante,

Ha sido un placer conversar contigo y conocer más sobre tus intereses y proyectos académicos. Aunque aún no hemos encontrado coincidencias en nuestra base de datos, tu perfil es muy prometedor y estoy seguro de que podríamos encontrar oportunidades de colaboración en el futuro.

Sigue trabajando duro y persiguiendo tus metas con determinación. Estoy aquí para apoyarte en lo que necesites y para ayudarte a construir una red de contactos que te impulse hacia el éxito en tu carrera profesional.

No dudes en contactarme si necesitas orientación o si surge alguna oportunidad que pueda ser de tu interés. ¡Estoy deseando verte crecer y alcanzar tus objetivos!

Saludos cordiales,
BAIT, Asistente Académico
```

