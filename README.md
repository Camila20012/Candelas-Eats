# Candelas-Eats
Aplicacion de comida Rapida

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".Activity.MainActivity">

    <ScrollView
        android:id="@+id/scrollView2"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:paddingBottom="70dp">

            <androidx.constraintlayout.widget.ConstraintLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_marginStart="24dp"
                android:layout_marginTop="16dp"
                android:layout_marginEnd="24dp">

                <ImageView
                    android:id="@+id/imageView"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    app:layout_constraintStart_toStartOf="parent"
                    app:layout_constraintTop_toTopOf="parent"
                    app:srcCompat="@drawable/profile" />

                <TextView
                    android:id="@+id/textView"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_marginStart="16dp"
                    android:layout_marginTop="12dp"
                    android:text="Usuario de"
                    android:textColor="@color/black"
                    app:layout_constraintStart_toEndOf="@+id/imageView"
                    app:layout_constraintTop_toTopOf="@+id/imageView" />

                <TextView
                    android:id="@+id/textView2"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Candelas"
                    android:textColor="@color/black"
                    android:textSize="18sp"
                    android:textStyle="bold"
                    app:layout_constraintBottom_toBottomOf="@+id/imageView"
                    app:layout_constraintStart_toStartOf="@+id/textView"
                    app:layout_constraintTop_toBottomOf="@+id/textView" />
            </androidx.constraintlayout.widget.ConstraintLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginStart="24dp"
                android:layout_marginTop="16dp"
                android:layout_marginEnd="24dp"
                android:background="@drawable/border_background"
                android:orientation="horizontal">

                <EditText
                    android:id="@+id/editTextTextPersonName"
                    android:layout_width="wrap_content"
                    android:layout_height="40dp"
                    android:layout_margin="3dp"
                    android:layout_weight="1"
                    android:background="@color/white"
                    android:drawableStart="@drawable/search"
                    android:drawablePadding="8dp"
                    android:ems="10"
                    android:hint="Buscar comida, Bebidas, etc"
                    android:inputType="textPersonName"
                    android:padding="8dp"
                    android:textSize="15sp" />

                <View
                    android:id="@+id/view"
                    android:layout_width="1dp"
                    android:layout_height="match_parent"
                    android:layout_marginTop="8dp"
                    android:layout_marginBottom="8dp"
                    android:background="@color/grey" />

                <ImageView
                    android:id="@+id/imageView2"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_margin="8dp"
                    app:srcCompat="@drawable/settings" />
            </LinearLayout>

            <androidx.constraintlayout.widget.ConstraintLayout
                android:layout_width="match_parent"
                android:layout_height="100dp"
                android:layout_marginStart="24dp"
                android:layout_marginTop="16dp"
                android:layout_marginEnd="24dp"
                android:background="@drawable/banner_background">

                <TextView
                    android:id="@+id/textView3"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_marginStart="24dp"
                    android:text="Cupon 2x1 gratis!"
                    android:textColor="@color/white"
                    android:textSize="18sp"
                    app:layout_constraintBottom_toBottomOf="parent"
                    app:layout_constraintStart_toStartOf="parent"
                    app:layout_constraintTop_toTopOf="parent" />

                <TextView
                    android:id="@+id/textView4"
                    android:layout_width="100dp"
                    android:layout_height="30dp"
                    android:layout_marginEnd="24dp"
                    android:background="@drawable/green_button_background"
                    android:gravity="center"
                    android:text="Ordenar ahora"
                    android:textColor="@color/white"
                    app:layout_constraintBottom_toBottomOf="parent"
                    app:layout_constraintEnd_toEndOf="parent"
                    app:layout_constraintTop_toTopOf="parent" />
            </androidx.constraintlayout.widget.ConstraintLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_marginStart="16dp"
                android:layout_marginTop="8dp"
                android:layout_marginEnd="16dp"
                android:orientation="vertical">

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:orientation="horizontal">

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:layout_width="0dp"
                        android:layout_height="match_parent"
                        android:layout_margin="8dp"
                        android:layout_weight="0.25"
                        android:background="@drawable/category_background">

                        <ImageView
                            android:id="@+id/imageView3"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_margin="10dp"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:srcCompat="@drawable/btn_1" />

                        <TextView
                            android:id="@+id/textView5"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Pizza"
                            android:textColor="@color/black"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="@+id/imageView3"
                            app:layout_constraintStart_toStartOf="@+id/imageView3"
                            app:layout_constraintTop_toBottomOf="@+id/imageView3" />
                    </androidx.constraintlayout.widget.ConstraintLayout>

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:layout_width="0dp"
                        android:layout_height="match_parent"
                        android:layout_margin="8dp"
                        android:layout_weight="0.25"
                        android:background="@drawable/category_background">

                        <ImageView
                            android:id="@+id/imageView3"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_margin="10dp"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:srcCompat="@drawable/btn_2" />

                        <TextView
                            android:id="@+id/textView5"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Burger"
                            android:textColor="@color/black"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="@+id/imageView3"
                            app:layout_constraintStart_toStartOf="@+id/imageView3"
                            app:layout_constraintTop_toBottomOf="@+id/imageView3" />
                    </androidx.constraintlayout.widget.ConstraintLayout>

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:layout_width="0dp"
                        android:layout_height="match_parent"
                        android:layout_margin="8dp"
                        android:layout_weight="0.25"
                        android:background="@drawable/category_background">

                        <ImageView
                            android:id="@+id/imageView3"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_margin="10dp"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:srcCompat="@drawable/btn_3" />

                        <TextView
                            android:id="@+id/textView5"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Pollo"
                            android:textColor="@color/black"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="@+id/imageView3"
                            app:layout_constraintStart_toStartOf="@+id/imageView3"
                            app:layout_constraintTop_toBottomOf="@+id/imageView3" />
                    </androidx.constraintlayout.widget.ConstraintLayout>

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:layout_width="0dp"
                        android:layout_height="80dp"
                        android:layout_margin="8dp"
                        android:layout_weight="0.25"
                        android:background="@drawable/category_background">

                        <ImageView
                            android:id="@+id/imageView3"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_margin="10dp"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:srcCompat="@drawable/btn_4" />

                        <TextView
                            android:id="@+id/textView5"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Hotdog"
                            android:textColor="@color/black"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="@+id/imageView3"
                            app:layout_constraintStart_toStartOf="@+id/imageView3"
                            app:layout_constraintTop_toBottomOf="@+id/imageView3" />
                    </androidx.constraintlayout.widget.ConstraintLayout>
                </LinearLayout>

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:orientation="horizontal">

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:layout_width="0dp"
                        android:layout_height="match_parent"
                        android:layout_margin="8dp"
                        android:layout_weight="0.25"
                        android:background="@drawable/category_background">

                        <ImageView
                            android:id="@+id/imageView3"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_margin="10dp"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:srcCompat="@drawable/btn_5" />

                        <TextView
                            android:id="@+id/textView5"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Sushi"
                            android:textColor="@color/black"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="@+id/imageView3"
                            app:layout_constraintStart_toStartOf="@+id/imageView3"
                            app:layout_constraintTop_toBottomOf="@+id/imageView3" />
                    </androidx.constraintlayout.widget.ConstraintLayout>

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:layout_width="0dp"
                        android:layout_height="match_parent"
                        android:layout_margin="8dp"
                        android:layout_weight="0.25"
                        android:background="@drawable/category_background">

                        <ImageView
                            android:id="@+id/imageView3"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_margin="10dp"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:srcCompat="@drawable/btn_6" />

                        <TextView
                            android:id="@+id/textView5"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Meat"
                            android:textColor="@color/black"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="@+id/imageView3"
                            app:layout_constraintStart_toStartOf="@+id/imageView3"
                            app:layout_constraintTop_toBottomOf="@+id/imageView3" />
                    </androidx.constraintlayout.widget.ConstraintLayout>

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:layout_width="0dp"
                        android:layout_height="match_parent"
                        android:layout_margin="8dp"
                        android:layout_weight="0.25"
                        android:background="@drawable/category_background">

                        <ImageView
                            android:id="@+id/imageView3"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_margin="10dp"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:srcCompat="@drawable/btn_7" />

                        <TextView
                            android:id="@+id/textView5"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Drinks"
                            android:textColor="@color/black"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="@+id/imageView3"
                            app:layout_constraintStart_toStartOf="@+id/imageView3"
                            app:layout_constraintTop_toBottomOf="@+id/imageView3" />
                    </androidx.constraintlayout.widget.ConstraintLayout>

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:layout_width="0dp"
                        android:layout_height="80dp"
                        android:layout_margin="8dp"
                        android:layout_weight="0.25"
                        android:background="@drawable/category_background">

                        <ImageView
                            android:id="@+id/imageView3"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_margin="10dp"
                            android:padding="8dp"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:srcCompat="@drawable/btn_8" />

                        <TextView
                            android:id="@+id/textView5"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Mas"
                            android:textColor="@color/black"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="@+id/imageView3"
                            app:layout_constraintStart_toStartOf="@+id/imageView3"
                            app:layout_constraintTop_toBottomOf="@+id/imageView3" />
                    </androidx.constraintlayout.widget.ConstraintLayout>
                </LinearLayout>
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_marginStart="24dp"
                android:layout_marginTop="8dp"
                android:layout_marginEnd="24dp"
                android:orientation="horizontal">

                <TextView
                    android:id="@+id/textView6"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="Calificacion alta de la ciudad"
                    android:textColor="@color/black"
                    android:textSize="18sp"
                    android:textStyle="bold" />

                <TextView
                    android:id="@+id/textView7"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="Ver mas"
                    android:textAlignment="viewEnd"
                    android:textColor="@color/green" />
            </LinearLayout>

            <androidx.recyclerview.widget.RecyclerView
                android:id="@+id/view1"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:clipToPadding="false"
                android:paddingStart="16dp"
                android:paddingEnd="16dp" />

        </LinearLayout>
    </ScrollView>

    <androidx.coordinatorlayout.widget.CoordinatorLayout
        android:layout_width="match_parent"
        android:layout_height="100dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent">

        <com.google.android.material.bottomappbar.BottomAppBar
            android:layout_width="match_parent"
            android:layout_gravity="bottom"
            android:layout_height="60dp">
            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:orientation="horizontal">

                <LinearLayout
                    android:id="@+id/homeBtn"
                    android:layout_width="0dp"
                    android:layout_height="match_parent"
                    android:layout_weight="0.25"
                    android:orientation="vertical">

                    <ImageView
                        android:id="@+id/imageView4"
                        android:layout_width="20dp"
                        android:layout_height="20dp"
                        android:layout_gravity="center"
                        android:layout_marginTop="4dp"
                        android:layout_weight="1"
                        app:srcCompat="@drawable/bottom_btn1" />

                    <TextView
                        android:id="@+id/textView8"
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:text="Home"
                        android:textAlignment="center"
                        android:textColor="@color/green" />
                </LinearLayout>

                <LinearLayout
                    android:id="@+id/cartBtn"
                    android:layout_width="0dp"
                    android:layout_height="match_parent"
                    android:layout_weight="0.25"
                    android:orientation="vertical">

                    <ImageView
                        android:id="@+id/imageView4"
                        android:layout_width="20dp"
                        android:layout_height="20dp"
                        android:layout_gravity="center"
                        android:layout_marginTop="4dp"
                        android:layout_weight="1"
                        app:srcCompat="@drawable/bottom_btn2" />

                    <TextView
                        android:id="@+id/textView8"
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:text="Cart"
                        android:textAlignment="center"
                        android:textColor="#959595" />
                </LinearLayout>

                <LinearLayout
                    android:layout_width="0dp"
                    android:layout_height="match_parent"
                    android:layout_weight="0.25"
                    android:orientation="vertical">

                    <ImageView
                        android:id="@+id/imageView4"
                        android:layout_width="20dp"
                        android:layout_height="20dp"
                        android:layout_gravity="center"
                        android:layout_marginTop="4dp"
                        android:layout_weight="1"
                        app:srcCompat="@drawable/bottom_btn3" />

                    <TextView
                        android:id="@+id/textView8"
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:text="Soporte"
                        android:textAlignment="center"
                        android:textColor="#959595" />
                </LinearLayout>

                <LinearLayout
                    android:layout_width="0dp"
                    android:layout_height="match_parent"
                    android:layout_weight="0.25"
                    android:orientation="vertical">

                    <ImageView
                        android:id="@+id/imageView4"
                        android:layout_width="20dp"
                        android:layout_height="20dp"
                        android:layout_gravity="center"
                        android:layout_marginTop="4dp"
                        android:layout_weight="1"
                        app:srcCompat="@drawable/bottom_btn4" />

                    <TextView
                        android:id="@+id/textView8"
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:text="Settings"
                        android:textAlignment="center"
                        android:textColor="#959595" />
                </LinearLayout>
            </LinearLayout>
        </com.google.android.material.bottomappbar.BottomAppBar>
    </androidx.coordinatorlayout.widget.CoordinatorLayout>
</androidx.constraintlayout.widget.ConstraintLayout>
