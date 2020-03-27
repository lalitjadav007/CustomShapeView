# jadav.lalit57-gmail.com
CustomShapeView

CustomShapeView is requirnment for almost every application. I have searched most of time how to make custom shape imageview. Recently I found most easy way of doing it, by using below code



//in xml you need to add attributes to imageview

        android:background="@drawable/bg_circle"
        android:outlineProvider="background"

//Set below line in code file

        imageView.clipToOutline = true



Is it that much easy? Yes, it is.



Note: It is only working for shape drawable (Not vector) and for android &gt;= 21.
