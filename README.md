Resources
	Referencing Resources
		In XML
			@string/string_name
			@drawable/image_name
			@style/style_name
		In Java
			R.id.string_name
			R.string.string_name
			R.drawable.icon

XML
	Using ID : @+id/object_name

JAVA
	Basic onCreate
		@Override     
		protected void onCreate(Bundle savedInstanceState) {         
			super.onCreate(savedInstanceState);         
			setContentView(R.layout.name_of_layout); 
		} 

	Sample Member Assignments
		mMyTextView = (TextView) findViewById(R.id.object_name);
		mMyButton = (Button) findViewById(R.id.object_name);

Toast
	Toast.makeText(my_class_name.this, string_here, Toast.LENGTH_SHORT).show();
