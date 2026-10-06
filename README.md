# Sistema Criptográfico y Gestor de Apuestas Seguras (UC3M)

Proyecto práctico desarrollado para la asignatura de Criptografía y Ciberseguridad en el Grado de Ingeniería Informática por la Universidad Carlos III de Madrid (UC3M).

## Características Principales

* **Autoridad de Certificación (CA) Propia:** Generación y gestión de claves privadas (`ca.key`), certificados raíz (`ca.pem`) y firma de certificados digitales.
* **Cifrado Híbrido:** Implementación de cifrado simétrico y asimétrico para garantizar la confidencialidad de la información.
* **Autenticación y Firma Digital:** Módulo de autenticación de usuarios y verificación de integridad mediante firma digital.
* **Aplicación Práctica (Gestor de Apuestas):** Software que utiliza la infraestructura criptográfica para procesar transacciones/apuestas de forma segura.
* **Batería de Tests Unitarios:** Pruebas integradas para validar el correcto funcionamiento de los algoritmos simétricos, asimétricos y esquemas de firma (`test_simetrico.py`, `test_asimetrico.py`, `test_firma_digital.py`).

## Tecnologías Utilizadas

* **Lenguaje:** Python 3
* **Criptografía:** PKI (Public Key Infrastructure), Cifrado Simétrico/Asimétrico, Firmas Digitales, Certificados X.509, Hashing
* **Herramientas:** Git, PyTest / Unittest
