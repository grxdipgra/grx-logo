Para modificar el logo splash de arranque debemos modificar los archivos:

/usr/share/plymouth/themes/kubuntu-logo/images

	logo-glow.png
	logo.png

Y por ultimo actualizar la imagen de arranque:

	update-initramfs -u

para modificar el de plasma kde:

/usr/share/plasma/look-and-feel/org.kde.breeze.desktop/contents/splash/images

O bien se modifican los que hay o bien se copian los nuevos y se cambia la ruta en el qml:

/usr/share/plasma/look-and-feel/org.kde.breeze.desktop/contents/splash/Splash.qml

Los fondos de pantalla se encuentran en:
/usr/share/wallpapers

El fondo por defecto es Next

/usr/share/wallpapers/Next
