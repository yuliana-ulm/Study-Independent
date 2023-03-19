-----praktikum awalan default kode

```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity2">

</androidx.constraintlayout.widget.ConstraintLayout>
```


----praktikum 1

```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto"
xmlns:tools="http://schemas.android.com/tools"
android:layout_width="match_parent"
android:layout_height="match_parent"
android:orientation="vertical"
android:paddingTop="10dp"
tools:context=".MainActivity">

<androidx.cardview.widget.CardView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_centerInParent="true"
    app:cardBackgroundColor="@color/purple_500"
    app:cardCornerRadius="20dp"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.327"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.224" />

</androidx.constraintlayout.widget.ConstraintLayout>
```


----praktikum 2

```xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto"
xmlns:tools="http://schemas.android.com/tools"
android:layout_width="match_parent"
android:layout_height="match_parent"
android:orientation="vertical"
android:paddingTop="10dp"
tools:context=".MainActivity">

<androidx.cardview.widget.CardView
    android:layout_width="200dp"
    android:layout_height="200dp"
    app:cardBackgroundColor="@color/purple_500"
    app:cardCornerRadius="20dp"
    android:layout_centerInParent="true"
    />
</RelativeLayout>
```


-----praktikum 3

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="horizontal"
    android:paddingTop="10dp"
    tools:context=".MainActivity">

    <androidx.cardview.widget.CardView
    android:layout_width="100dp"
    android:layout_height="200dp"
        android:layout_marginHorizontal="8dp"
    app:cardBackgroundColor="@color/purple_200"
    app:cardCornerRadius="20dp"
        android:layout_weight="1"
    />
    <androidx.cardview.widget.CardView
        android:layout_marginHorizontal="8dp"
        android:layout_width="100dp"
        android:layout_height="200dp"
        app:cardBackgroundColor="@color/purple_200"
        app:cardCornerRadius="20dp"
        android:layout_weight="1"
        />
    <androidx.cardview.widget.CardView
        android:layout_marginHorizontal="8dp"
        android:layout_width="100dp"
        android:layout_height="200dp"
        app:cardBackgroundColor="@color/purple_200"
        app:cardCornerRadius="20dp"
        android:layout_weight="1"
        />

</LinearLayout>
```
