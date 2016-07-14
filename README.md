# vtkOBJWriter
vtkOBJWriter is a wavefront OBJ writer based on VTK。

It also support compress output like this:

	vtkSmartPointer<vtkOBJWriter> writer = vtkSmartPointer<vtkOBJWriter>::New();
	
	writer->SetOutputCompressed(true);

