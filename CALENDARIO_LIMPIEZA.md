# Calendario de Limpieza — Basconia Smart Studio

## Reservas actuales

| Check-out (día limpieza) | Huéspedes | Nombre | Plataforma |
|---|---|---|---|
| 5 mayo | 2 | Denis George Grosu | Booking |
| 8 mayo | 2 | Ela Bencková | Booking |
| 25 mayo | 1 | Marcos Serna Donaire | Booking |
| 31 mayo | 3 | Andrés Sancho | Booking |
| 3 junio | 2 | Youssef Aboudi | Booking |
| 7 junio | 2 | Mimon Hamed Mohamdd | Booking |
| 13 junio | 3 | Philip (grupo) | Airbnb |
| 22 junio | 3 (2+1 niño) | Reda Bibeche | Booking |
| 18 julio | 2 | Sandra Pardo de Santayana | Booking |
| 24 julio | 2 | Ginevra Prunecchi | Booking |

---

## Configuración Google Calendar

### Paso 1: Crear calendario dedicado
1. Abre Google Calendar (calendar.google.com)
2. En la barra izquierda, junto a "Otros calendarios", pulsa **+**
3. Selecciona **Crear un calendario**
4. Nombre: `Limpieza Basconia`
5. Pulsa **Crear calendario**

### Paso 2: Añadir las reservas como eventos
Para cada reserva, crea un evento en el **día de check-out** (que es cuando toca limpiar):

1. Haz clic en el día de check-out
2. Título del evento: `🧹 Limpieza - X personas`
   - Ejemplo: `🧹 Limpieza - 2 personas`
3. Hora: 11:00 - 13:00 (o el horario que acuerdes con la limpiadora)
4. Guardar

### Paso 3: Compartir con la limpiadora
1. En la barra izquierda, pasa el ratón sobre "Limpieza Basconia"
2. Pulsa los 3 puntos (⋮) → **Configuración y uso compartido**
3. En "Compartir con personas concretas" → **Añadir personas**
4. Escribe el email de la limpiadora
5. Permisos: **Ver todos los detalles del evento**
6. Pulsa **Enviar**

La limpiadora recibirá un email para aceptar. Una vez acepte, le aparecerá el calendario automáticamente en su Google Calendar del móvil.

### Paso 4: Cuando llegue una nueva reserva
1. Abre Google Calendar
2. Ve al día de **check-out** de la nueva reserva
3. Crea evento: `🧹 Limpieza - X personas`
4. Listo — la limpiadora lo ve automáticamente

---

## Formato de los eventos (para que la limpiadora lo entienda fácil)

```
Título: 🧹 Limpieza - 2 personas
Hora: 11:00 - 13:00
Descripción (opcional): Check-out a las 11:00. Siguiente check-in a las 14:00.
```

Si hay check-in el mismo día, añade en descripción:
```
⚠️ Entran huéspedes hoy a las 14:00
```

---

## Futuro: automatización con n8n
Cuando montes n8n, se puede automatizar:
- Email de nueva reserva → parsear datos → crear evento en Google Calendar automáticamente
- Incluir nº huéspedes, hora check-out, si hay check-in el mismo día
