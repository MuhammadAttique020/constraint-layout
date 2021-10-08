# constraint-layout

<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/images"
    android:textAlignment="center"
    tools:context=".MainActivity">

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/logo" />

    <TextView
        android:id="@+id/signin"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Sign in"
        android:textColor="#100A0A"
        android:textSize="50dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.132" />

    <EditText
        android:id="@+id/editTextTextPersonName3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:drawableLeft="@drawable/ic_person"
        android:drawablePadding="20dp"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="User Name"
        android:textColor="#150E0E"
        android:textSize="20sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/signin"
        app:layout_constraintStart_toStartOf="@+id/signin"
        app:layout_constraintTop_toBottomOf="@+id/signin"
        app:layout_constraintVertical_bias="0.133" />

    <EditText
        android:id="@+id/editTextTextPersonName4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:drawableLeft="@drawable/ic_info"
        android:drawablePadding="20dp"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="password"
        android:textColor="#0E0909"
        android:textSize="20sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/editTextTextPersonName3"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="@+id/editTextTextPersonName3"
        app:layout_constraintTop_toBottomOf="@+id/editTextTextPersonName3"
        app:layout_constraintVertical_bias="0.097" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:backgroundTint="#834C4C"
        android:text="Log in"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/editTextTextPersonName4"
        app:layout_constraintStart_toStartOf="@+id/editTextTextPersonName4"
        app:layout_constraintTop_toBottomOf="@+id/editTextTextPersonName4"
        app:layout_constraintVertical_bias="0.083" />

    <TextView
        android:id="@+id/textView3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Forgot password"
        android:textColor="#100B0B"
        android:textSize="24sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/button"
        app:layout_constraintHorizontal_bias="0.365"
        app:layout_constraintStart_toStartOf="@+id/button"
        app:layout_constraintTop_toBottomOf="@+id/button"
        app:layout_constraintVertical_bias="0.416" />

</androidx.constraintlayout.widget.ConstraintLayout>
