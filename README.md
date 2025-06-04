# 🛡️ Análisis con Nikto sobre OWASP Juice Shop  
Este repositorio contiene los resultados del análisis de vulnerabilidades realizado con la herramienta de escaneo web **Nikto**, sobre la aplicación vulnerable **OWASP Juice Shop** desplegada localmente. 
El análisis se llevó a cabo en un entorno controlado con fines educativos.

---

## 📌 Características destacadas
- Escaneo completo de un servidor web simulado, desplegado exclusivamente con fines educativos, (localhost:3000) con Nikto.
- Detección de cabeceras inseguras, archivos públicos, rutas sospechosas y posibles backups.
- Resultados exportados en dos formatos: `.txt` y `.html` para facilitar su revisión y análisis.

## 🌐 ¿Qué incluye?

### 📄 Escaneo completo (.txt)  
Registro de todas las rutas exploradas, métodos HTTP y advertencias generadas por Nikto al analizar Juice Shop con la opción básica.

### ⚠️ Vulnerabilidades críticas (.html)  
Informe en formato visual con las vulnerabilidades más relevantes detectadas mediante el flag `-Tuning 1`.

## 🛠️ Herramientas utilizadas
- Máquina virtual Kali Linux, alojada en oracle VM VirtualBox.
- Nikto
- OWASP Juice Shop 
- Mozilla Firefox como navegador principal de la máquina.

## 🎓 Objetivo
Aprender a utilizar Nikto para detectar configuraciones inseguras en un servidor web. Esta práctica permite familiarizarse con la lectura de resultados de escáneres automáticos y con los riesgos más comunes en aplicaciones web.
Este proyecto puede servir como **material de referencia y práctica** para reforzar conceptos clave.

## 🚀 Cómo usar
### Uso de este análisis:
1. Clonar el repositorio o descargar los archivos.
2. Abrir `nikto_juiceshop.html` con tu navegador para revisar el informe visual.
3. Leer `analisis_juiceshop_nikto.txt` con un editor de texto para explorar los detalles técnicos del escaneo.

### Ejecución desde 0:
1. Instalar VirtualBox. [Descargar VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. Instalar en VirtualBox una máquina con Kali Linux [Descargar Kali Linux](https://www.kali.org/get-kali/#kali-platforms)
3. Iniciar la máquina e instalar NodeJS v.22 [Descargar NodeJS](https://nodejs.org/en/download/current)
4. Descomprimir el fichero y copiar los archivos necesarios en el usuario con el comando:
```bash
sudo cp -r node-v22.12.0-linux-x64/{bin,include,lib,share} /usr/
```
5. Descargar OWASP Juice Shop, versión para NodeJS, versión 24 y Linux de 64 bits. [Descargar Juice Shop](https://github.com/juice-shop/juice-shop)
6. Descomprimir el fichero obtenido de la descarga, entrar en él y ejecutar el comando:
```bash
sudo npm start
```
7. Una vez ejecutado ese comando, debemos buscar el puerto de escucha.
8. Abriremos el navegador e introduciremos la dirección ***127.0.0.1:[puerto_de_escucha]*** para entrar.
9. Seguir la documentación de la práctica.

## 📝 Explicación
El PDF con todas las explicaciones para replicar esta práctica se encuentra aqui:
🔗 [Documentación Nikto](https://github.com/nerxtkd/Documentaciones/blob/8113411db7dc5beb82128628a727ac6fb69ce6cb/UT03_Actividad2_Nikto_JuiceShop.pdf)

## 📌 Notas:
Este trabajo fue realizado como parte de mi proceso de aprendizaje en el análisis de vulnerabilidades.
Todos los ejercicios fueron desarrollados durante el curso de especialización en Ciberseguridad.

## 👩‍💻 Autora  
Trabajo realizado por Nerea C.  
🔗 Puedes ver otros proyectos en mi perfil de GitHub: [@nerxtkd](https://github.com/nerxtkd)


