# Glosario Técnico: Estándares Héctor Enrique

Este glosario define los términos clave utilizados para describir la arquitectura, seguridad y filosofía de nuestros proyectos.

## 🏛️ Arquitectura & Integridad

### Integridad Operativa (Operational Integrity)
La garantía de que un sistema se comportará exactamente según su diseño funcional, incluso bajo estrés extremo, fallos de hardware o intentos de manipulación maliciosa. Es la unión de la fiabilidad del software con la seguridad física.

### Zero Trust Architecture (Confianza Cero)
Modelo de seguridad que asume que la red está comprometida. Ninguna entidad (usuario, dispositivo o servicio) es confiable por defecto, y cada solicitud debe ser verificada independientemente del origen.

### Atestación de Hardware (Hardware Attestation)
Proceso mediante el cual un dispositivo prueba que su hardware (ej. TPM o TEE) es genuino y que el software que se ejecuta en él no ha sido alterado.

---

## 🔐 Seguridad & Criptografía

### Timing Attack (Ataque de Tiempo)
Un tipo de ataque de canal lateral en el que un atacante intenta comprometer un criptosistema analizando el tiempo que tarda la computadora en ejecutar algoritmos o comparaciones. Mitigamos esto usando `MessageDigest.isEqual()`.

### Coordinated Vulnerability Disclosure (CVD)
Modelo de divulgación donde el descubridor de una vulnerabilidad trabaja de forma privada con los desarrolladores para asegurar que se implemente un parche antes de que los detalles del fallo se hagan públicos.

---

## ⚡ Metodología

### Vibe Coding
Enfoque de desarrollo ágil que prioriza el flujo creativo, el prototipado rápido y la intuición técnica ("the vibe"), sin sacrificar el rigor de la seguridad estructural en las fases finales del prototipo.

### Secure Development Lifecycle (SDL)
Conjunto de prácticas de ingeniería de software diseñadas para aumentar la seguridad y el cumplimiento de los sistemas en cada fase del desarrollo.
