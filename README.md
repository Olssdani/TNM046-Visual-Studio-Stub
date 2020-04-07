# TNM046-Visual-Studio-Stub
Skillnaden mot labskalet för codeblocks är att Utilities::Loadextensions() är utbytt mot glad som gör allt automatiskt via 
if (!gladLoadGLLoader((GLADloadproc)glfwGetProcAddress))
{
        std::cout << "Failed to initialize GLAD" << std::endl;
        return -1;
}

Mappen med meshes saknas och behövs laddas ner externt.
