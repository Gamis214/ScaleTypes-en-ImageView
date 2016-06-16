# ScaleTypes en ImageView
Diferentes tipos de Escalas para usar dentro de un Componente (ImageView)

###Tipos de escalas

####Matrix:
![Matrix](http://2.bp.blogspot.com/-LLnEzgXntT4/TdFiScQRujI/AAAAAAAAABk/rYR_sAxwBQ0/s300/fill_parent_matrix.png) ![alt text](http://1.bp.blogspot.com/-B5hOD5MXDrg/TdFiYhjn9aI/AAAAAAAAABs/gdZw2NPjmPw/s300/matrix.png)

####fitXY:
![Matrix](http://3.bp.blogspot.com/-U1FGl3FaRNg/TdFiqdJ-JdI/AAAAAAAAAB8/TF-k1CCNsnI/s300/fill_parent_fitXYpng.png) ![alt text](http://2.bp.blogspot.com/-pGHVPudpdz8/TdFiwd7VGnI/AAAAAAAAACE/tMPNDYw3WqE/s300/fitXY.png)

####fitStart:
![Matrix](http://3.bp.blogspot.com/-Hxyvx10QHm8/TdFi_a1qJzI/AAAAAAAAACU/GZgFf9fRCSE/s300/fill_parent_fitstart.png) ![alt text](http://4.bp.blogspot.com/-g3ZXZUwpV2Q/TdFjDy1VzpI/AAAAAAAAACc/mkcE6Dm9Wfo/s300/fitStart.png)

####fitCenter:
![Matrix](http://1.bp.blogspot.com/-G4Ps3_N4oAU/TdFjVI3VcXI/AAAAAAAAACs/KcGsn9zQpwk/s300/fill_parent_fitCenter.png) ![alt text](http://1.bp.blogspot.com/-jdHe075v420/TdFjaeXsRrI/AAAAAAAAAC0/HWSyBYNsXmg/s300/fitCenter.png)

####fitEnd:
![Matrix](http://4.bp.blogspot.com/-jmzFvi7VPWg/TdFjrHp4ECI/AAAAAAAAADE/ho16tifSxgc/s300/fill_parent_fitEnd.png) ![alt text](http://4.bp.blogspot.com/-eDUqH-3owd4/TdFjxbqzQjI/AAAAAAAAADM/WDQfpo8uTG8/s300/fitEnd.png)

####center:
![Matrix](http://4.bp.blogspot.com/-j2crLGIj9S4/TdFj9CjUbRI/AAAAAAAAADc/Pav_V4etP-c/s300/fill_parent_center.png) ![alt text](http://1.bp.blogspot.com/-WXrw_rdE_eo/TdFkBPmRqiI/AAAAAAAAADk/jGXFhlQWqWg/s300/center.png)

####centerCrop:
![Matrix](http://3.bp.blogspot.com/-h_4yRzhbsIo/TdFkZqTVKkI/AAAAAAAAAD0/orXJt4hRLNY/s300/fill_parent_centerCrop.png) ![alt text](http://4.bp.blogspot.com/-6WsksXEQBCg/TdFkgoJCVuI/AAAAAAAAAD8/lk3QOp5ainY/s300/centerCrop.png)

####centerInside:
![Matrix](http://2.bp.blogspot.com/-DSq60peedII/TdFk1ctddaI/AAAAAAAAAEM/6tP2viFT22A/s300/fill_parent_centerInside.png) ![alt text](http://4.bp.blogspot.com/-DvUT4lOAqY8/TdFk8T_XD6I/AAAAAAAAAEU/a5VUsihhtGo/s300/centerInside.png)

###Aplicacion
Estos tipos de escalas son utilizados dentro de nuestro XML con las siguientes propiedades:
```xml
 <?xml version="1.0" encoding="utf-8"?>  
 <FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"  
   android:layout_width="fill_parent"  
   android:layout_height="fill_parent">  
   <ImageView android:layout_width="fill_parent"  
               android:layout_height="fill_parent"  
               android:src="@drawable/eureka"  
               android:scaleType="matrix">  
   </ImageView>  
 </FrameLayout>  
```
