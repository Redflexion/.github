# Política de Seguridad - Redflexion Consultores

Este proyecto se desarrolla bajo las directrices del **Esquema Nacional de Seguridad (ENS)** en su nivel de seguridad aplicable.

## Notificación de incidencias de seguridad
Si identificas cualquier vulnerabilidad, secreto expuesto o fallo de seguridad en este repositorio:

1. **NO publiques el problema en un Issue público.**
2. Envía un correo cifrado o reporte urgente a: `ti@redflexion.com`
3. Incluye:
   - Repositorio y rama afectada.
   - Descripción técnica y pasos para reproducir.
   - Nivel de impacto estimado.

## Requisitos de Desarrollo Seguro
Todo colaborador debe asegurar:
- Análisis estático previo al merge (SAST Semgrep).
- Firmado digital de commits (GPG/SSH).
- Prohibición estricta de incluir credenciales o datos reales de clientes en el código.