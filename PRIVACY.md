---
layout: default
title: Política de Privacidad
permalink: /privacy/
---

# Política de Privacidad - Co-Kitchen

**Última actualización:** 22 de mayo de 2026
**Responsable:** Diego Charro (bluedebug.contact@gmail.com)

Esta Política de Privacidad explica qué datos personales recopilamos cuando usas Co-Kitchen (en adelante, "la App"), con qué fines, dónde se almacenan y qué derechos tienes sobre ellos. Cumplimos con el Reglamento General de Protección de Datos (RGPD, UE 2016/679) y la Ley Orgánica 3/2018 de Protección de Datos Personales (LOPD-GDD) de España.

---

## 1. Datos que recopilamos

### 1.1. Datos que tú proporcionas
- **Cuenta de usuario:** email, contraseña (cifrada), nombre para mostrar.
- **Grupos compartidos:** nombre del grupo, miembros invitados.
- **Inventario y lista de compra:** productos, cantidades, fechas de caducidad estimadas.
- **Comandos de voz:** texto transcrito que envías deliberadamente al asistente.
- **Tickets de compra (opcional):** fotos que decides subir para extracción automática de items y precios.

### 1.2. Datos generados por el uso
- Identificadores anónimos del dispositivo (para sincronización en tiempo real).
- Logs técnicos de errores (sin contenido personal).
- Fechas de creación/modificación de cada item.

### 1.3. Datos que NO recopilamos
- No registramos audio. Sólo procesamos el texto transcrito por tu dispositivo.
- No accedemos a tu lista de contactos, ubicación, ni a otras apps de tu móvil.
- No usamos cookies de seguimiento publicitario.

---

## 2. Cómo usamos tus datos

| Finalidad | Base legal RGPD |
|-----------|-----------------|
| Autenticarte e identificarte como miembro de tu(s) grupo(s) | Ejecución del contrato (Art. 6.1.b) |
| Sincronizar inventario y lista de compra entre miembros del grupo | Ejecución del contrato (Art. 6.1.b) |
| Procesar comandos de voz mediante IA para identificar acciones e items | Ejecución del contrato (Art. 6.1.b) |
| Procesar tickets fotografiados para extraer items y precios | Consentimiento explícito (Art. 6.1.a) |
| Detectar y prevenir abusos (rate limiting, anti-spam) | Interés legítimo (Art. 6.1.f) |
| Mejorar el servicio mediante estadísticas agregadas y anonimizadas | Interés legítimo (Art. 6.1.f) |

**Nunca vendemos tus datos personales.**

---

## 3. Procesadores externos (subencargados)

Tus datos son tratados por los siguientes proveedores, todos con garantías de cumplimiento RGPD:

| Proveedor | Servicio | Localización | Política |
|-----------|----------|--------------|----------|
| Supabase Inc. | Autenticación, base de datos, almacenamiento, sincronización en tiempo real, edge functions | UE (eu-west-1, Irlanda) | https://supabase.com/privacy |
| Google LLC (Gemini API) | Procesamiento de texto de voz y reconocimiento de tickets de compra mediante IA | UE / global, con cláusulas contractuales tipo de la UE | https://cloud.google.com/terms/data-processing-addendum |

Los datos enviados a Google Gemini se procesan en tiempo real para la finalidad indicada y **no se utilizan para entrenar modelos**, conforme a los términos vigentes de Google Cloud AI Platform.

---

## 4. Datos compartidos dentro de un grupo

Cuando te unes a un grupo, **otros miembros del grupo pueden ver:**
- Tu nombre de usuario.
- El inventario, lista de compra, tickets y logs de consumo del grupo.
- Quién añadió, editó o consumió cada item.

**Otros miembros NO pueden ver:**
- Tu email.
- Tus otros grupos.
- Tu contraseña.

Antes de aceptar una invitación a un grupo, el inventario del grupo NO es visible para ti.

---

## 5. Tiempo de conservación

| Dato | Conservación |
|------|--------------|
| Cuenta y perfil | Mientras tengas cuenta activa. Al borrar, eliminación en 30 días. |
| Inventario y lista de compra | Mientras pertenezcas al grupo. |
| Logs de consumo | 12 meses (para historial de gasto e inflación personal). |
| Imágenes de tickets | Configurable: 24h o hasta que la borres manualmente (por defecto NO se guardan). |
| Logs técnicos | 90 días. |

Al eliminar tu cuenta, todos los datos personalmente identificables se borran. Los datos que aportaste a un grupo permanecen asociados al grupo pero anonimizados (ej: "Usuario eliminado") para no romper el historial de los demás miembros.

---

## 6. Tus derechos (RGPD)

Tienes derecho a:
1. **Acceso** — saber qué datos tenemos sobre ti.
2. **Rectificación** — corregir datos incorrectos.
3. **Supresión** — eliminar tu cuenta y datos.
4. **Limitación** — pedir que dejemos de usar ciertos datos.
5. **Portabilidad** — exportar tus datos en formato JSON.
6. **Oposición** — oponerte a tratamientos basados en interés legítimo.
7. **Retirar el consentimiento** en cualquier momento (sin efectos retroactivos).

**Cómo ejercerlos:** envía un email a `bluedebug.contact@gmail.com` desde la dirección asociada a tu cuenta. Respondemos en máximo 30 días.

También puedes eliminar tu cuenta y todos los datos personales asociados directamente desde la propia app, en Ajustes → "Borrar mi cuenta".

Tienes derecho a reclamar ante la **Agencia Española de Protección de Datos (AEPD)** si consideras que no atendemos tu solicitud: https://www.aepd.es

---

## 7. Menores de edad

Co-Kitchen **no está dirigida a menores de 14 años**. No recopilamos conscientemente datos de menores. Si descubrimos que un menor ha creado cuenta sin consentimiento parental, la eliminaremos.

---

## 8. Seguridad

Aplicamos medidas técnicas y organizativas adecuadas:
- Contraseñas cifradas (hash + sal).
- Conexiones HTTPS/TLS 1.3 con cifrado en tránsito.
- Aislamiento por grupo mediante Row Level Security a nivel de base de datos.
- Servidores en la UE con copias de seguridad cifradas.
- Acceso a producción restringido y registrado.

Ningún sistema es 100% seguro. En caso de brecha de datos, notificaremos a los usuarios afectados y a la AEPD en menos de 72 horas según exige el RGPD.

---

## 9. Cambios en esta política

Si modificamos esta política, te avisaremos en la app y por email con al menos 30 días de antelación. Si los cambios afectan a tus derechos, requeriremos tu consentimiento explícito.

---

## 10. Contacto

- **Email:** bluedebug.contact@gmail.com
- **Responsable del tratamiento:** Diego Charro
- **Jurisdicción:** España

Los datos identificativos completos del responsable (domicilio fiscal, NIF en su caso) se facilitarán mediante solicitud escrita al email de contacto, conforme al art. 13 RGPD.
