# Métodos Iterativos — DAT-243

Aplicación web interactiva para resolver sistemas de ecuaciones lineales
mediante tres métodos iterativos: **Gauss-Seidel**, **SOR** y **Gradiente Conjugado**.

## 🌐 Demo en vivo

**[→ Abrir aplicación](https://TU-USUARIO.github.io/metodos-iterativos/)**

## ✨ Funcionalidades

| Funcionalidad | Descripción |
|---|---|
| **Entrada manual** | Grilla editable para ingresar A y b por teclado |
| **CSV upload** | Carga matriz A y vector b desde archivos .csv (drag & drop) |
| **Validación** | Verifica simetría, DD, SPD antes de ejecutar |
| **ω automático** | Calcula ω_opt(SOR) mediante iteración de potencias |
| **Animación** | Curvas de convergencia animadas con Plotly (play/pause/slider) |
| **Tablas** | Iteraciones completas de los 3 métodos, descargables en CSV |
| **Comparativa** | Gráfica y tabla comparativa con análisis automático |
| **Ejemplos** | Pre-cargados: circuito 12×12 y sistema 5×5 |

## 🚀 Despliegue en GitHub Pages

```bash
# 1. Crear repositorio en GitHub
# 2. Subir el archivo index.html
git init
git add index.html README.md
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/metodos-iterativos.git
git push -u origin main

# 3. En GitHub: Settings → Pages → Source: main branch / root
# 4. La URL será: https://TU-USUARIO.github.io/metodos-iterativos/
```

## 📄 Formato del CSV

**Matriz A** (n×n):
```
0.188571,-0.1,0.0,...
-0.1,0.260335,-0.066667,...
...
```

**Vector b** (n valores, una fila o una columna):
```
2.0,0.5,1.5,-1.0,0.0,1.0,-0.5,0.0,3.0,0.0,-1.5,-2.5
```

## 🧮 Métodos implementados

- **Gauss-Seidel**: actualización in-situ, convergencia O(κ)
- **SOR**: parámetro ω editable o auto-calculado, convergencia O(√κ)  
- **Gradiente Conjugado**: para matrices SPD, convergencia en ≤ n pasos

## 📚 Asignatura

DAT-243 — Métodos Numéricos  
Universidad Mayor de San Andrés — UMSA  
Estudiante: Enrrique Julio Alvarado Mamani  
Docente: Lic. Brígida Carvajal
# Num
