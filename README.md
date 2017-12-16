<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.anu_person_details.MainActivity">
       <TextView
        android:id="@+id/textView1"
        android:layout_width="184dp"
        android:layout_height="21dp"
        android:text="Welcome To Person InfoEnroll App"
        tools:layout_editor_absoluteX="76dp"
        tools:layout_editor_absoluteY="16dp"
        android:layout_alignParentTop="true"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="18dp" />
    <TextView
        android:id="@+id/textView2"
        android:layout_width="169dp"
        android:layout_height="45dp"
        android:text="Person Name"
        tools:layout_editor_absoluteX="16dp"
        tools:layout_editor_absoluteY="74dp"
        android:layout_marginBottom="36dp"
        android:layout_above="@+id/button1"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_marginLeft="12dp"
        android:layout_marginStart="12dp"
         />
    <EditText
        android:id="@+id/editText1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="textPersonName"
        tools:layout_editor_absoluteY="320dp"
        tools:layout_editor_absoluteX="120dp"
        android:layout_alignRight="@+id/button1"
        android:layout_alignEnd="@+id/button1"
        android:layout_alignBottom="@+id/textView2" />
     <TextView
        android:id="@+id/textView3"
        android:layout_width="169dp"
        android:layout_height="45dp"
        android:text="Age"
        tools:layout_editor_absoluteX="18dp"
        tools:layout_editor_absoluteY="76dp"
        android:layout_marginBottom="36dp"
        android:layout_above="@+id/button2"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_marginLeft="12dp"
        android:layout_marginStart="12dp"
         />
    <EditText
        android:id="@+id/editText2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="numberSigned"
        tools:layout_editor_absoluteY="330dp"
        tools:layout_editor_absoluteX="130dp"
        android:layout_alignRight="@+id/button2"
        android:layout_alignEnd="@+id/button2"
        android:layout_alignBottom="@+id/textView3" />
     <TextView
        android:id="@+id/textView4"
        android:layout_width="169dp"
        android:layout_height="45dp"
        android:text="Gender"
        tools:layout_editor_absoluteX="20dp"
        tools:layout_editor_absoluteY="78dp"
        android:layout_marginBottom="38dp"
        android:layout_above="@+id/button3"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_marginLeft="12dp"
        android:layout_marginStart="12dp"
         />
    <EditText
        android:id="@+id/editText3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="text"
        tools:layout_editor_absoluteY="350dp"
        tools:layout_editor_absoluteX="150dp"
        android:layout_alignRight="@+id/button3"
        android:layout_alignEnd="@+id/button3"
        android:layout_alignBottom="@+id/textView4" />
     <TextView
        android:id="@+id/textView5"
        android:layout_width="169dp"
        android:layout_height="45dp"
        android:text="Group Name1 And ID"
        tools:layout_editor_absoluteX="22dp"
        tools:layout_editor_absoluteY="80dp"
        android:layout_marginBottom="40dp"
        android:layout_above="@+id/button4"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_marginLeft="12dp"
        android:layout_marginStart="12dp"
         />
    <EditText
        android:id="@+id/editText4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="text|number|numberSigned"
        tools:layout_editor_absoluteY="370dp"
        tools:layout_editor_absoluteX="170dp"
        android:layout_alignRight="@+id/button4"
        android:layout_alignEnd="@+id/button4"
        android:layout_alignBottom="@+id/textView5" /> 
      <TextView
        android:id="@+id/textView6"
        android:layout_width="169dp"
        android:layout_height="45dp"
        android:text="Start Date"
        tools:layout_editor_absoluteX="24dp"
        tools:layout_editor_absoluteY="82dp"
        android:layout_marginBottom="42dp"
        android:layout_above="@+id/button5"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_marginLeft="12dp"
        android:layout_marginStart="12dp"
         />
    <EditText
        android:id="@+id/editText5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="number|numberSigned"
        tools:layout_editor_absoluteY="390dp"
        tools:layout_editor_absoluteX="190dp"
        android:layout_alignRight="@+id/button5"
        android:layout_alignEnd="@+id/button5"
        android:layout_alignBottom="@+id/textView6" />
    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Submit"
        android:onClick="Submit"
        android:layout_marginLeft="74dp"
        android:layout_marginStart="74dp" />
        android:layout_toEndof="@+id/button6"/>
   </RelativeLayout>
        
       
       
        
        
