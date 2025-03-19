**Descripción General**
El proyecto "ProyectoAPP" es una aplicación móvil desarrollada en Kotlin para la plataforma Android. La configuración del manifiesto (AndroidManifest.xml) sugiere que la aplicación tiene varias características y servicios configurados.

**Características Principales**

Permisos:
La aplicación solicita permiso para acceder a Internet (android.permission.INTERNET).

Configuración de la Aplicación:
La aplicación se llama GroceriesStoreApplication.
Tiene configuraciones para permitir copias de seguridad (android:allowBackup="true").
Usa aceleración por hardware (android:hardwareAccelerated="true").
Tiene un ícono y un ícono redondo personalizados (android:icon y android:roundIcon).
Soporta diseño RTL (de derecha a izquierda) (android:supportsRtl="true").
Usa un tema personalizado llamado SplashTheme.

Meta-datos de Firebase:
Configura los meta-datos para Firebase Cloud Messaging, incluyendo un ícono de notificación por defecto y un color de notificación.
Servicios

FirebaseCloudMessageService: Un servicio para manejar eventos de mensajería de Firebase (com.google.firebase.MESSAGING_EVENT).
Actividades

OnboardingActivity: Esta actividad es la pantalla principal (MAIN) y la lanzadora (LAUNCHER) de la aplicación.
AuthActivity: Una actividad probablemente relacionada con la autenticación de usuarios.
MainActivity: La actividad principal de la aplicación con una configuración especial para el modo de entrada de teclado (adjustNothing).

Lenguaje Utilizado
Kotlin: El 100% del código del proyecto está escrito en Kotlin.
