# themes_10
temas movil
install 
Plataforma: Android Studio 3.4.2

1.Clic derecho sobre el proyecto > New > Module > Import .JAR/ .ARR Package

2.Seleccionar la librería ydar en Finish.

3.Añadir lo siguiente en build.gradle(Module:app).

dependencies {
    ...   
    implementation project(':xxxxxxx-release')    
    ...
}

4.Sincronizar Gradle dando en 'Sync now'.