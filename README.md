# CornerzDashboard
Dashboard
 xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">
    <android.support.v4.widget.NestedScrollView
        android:layout_width="match_parent"
        android:layout_height="match_parent"></android.support.v4.widget.NestedScrollView>
            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent">
                android:orentation="vertical"
                >
                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="240dp"
                    android:background="@drawable/cornerz2"
                    android:textAlignment="center"
                    android:text="Cornerz Dashboard"
                    android:textsize="24sp"
                    android:gravity="bottom"
                    android:textColor="Black"


                    />

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:orientation="horizontal"
                    android:weightSum="3"

                    >
                    <LinearLayout
                        android:layout_width="0dp"
                        android:layout_height="120dp"
                        android:layout_weight="1"
                        android:layout_margin="2dp"
                        android:orientation="vertical"
                        android:background="@color/colorGrapeFruit"

                        >
                        <ImageView
                            android:layout_width="30dp"
                            android:layout_height="30dp"
                            android:layout_marginTop="20dp"
                            android:layout_gravity="center"
                            android:scr="@drawable/ic_icon_archary"
                            android:tint="@color/white"


                            />
                            <TextView
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:padding="8dp"
                                android:layout_marginTop="30dp"
                                android:background="@color/colorGrapeFruitDark"
                                android:text="Archary"
                                android:textAligment="center"
                                android:textColor="@color/colorwhite"


                                />

                    </LinearLayout>

                </LinearLayout>

            </LinearLayout>
<!-- Second Row-->

    <!--EndSecond Row-->


</ScrollView>

</LinearLayout>
