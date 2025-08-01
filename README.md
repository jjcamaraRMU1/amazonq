# Multi-Employee UIT Checker

## Descripción
Script para verificar el UIT (Unknown Idle Time) por AA, quitando descansos y Load Line Injection/HR_GROUP_EVENTS, y mostrando el porcentaje en base a Stow + Decant/Prep.

## Características
- Cálculo de UIT eliminando tiempos de descanso
- Exclusión de Load Line Injection y HR_GROUP_EVENTS
- Cálculo de porcentaje UIT basado en tiempo trabajado
- Soporte para múltiples empleados
- Interfaz visual mejorada

## Instalación
1. Instalar Tampermonkey o Violentmonkey en tu navegador
2. Crear nuevo script
3. Copiar y pegar el contenido del archivo `scripts/multiEmployeeUIT.js`
4. Guardar el script

## Uso
1. Navegar a FCLM Portal
2. Ingresar los IDs de empleados (uno por línea)
3. Hacer clic en "Verificar UIT"
4. Los resultados mostrarán UIT en minutos y porcentaje

## Versión
2.0
