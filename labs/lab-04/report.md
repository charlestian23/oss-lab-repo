## CMake Tutorial
### Part 1
#### Step 1
Console Output:

![image](https://user-images.githubusercontent.com/46334090/174331231-7257984b-ab75-4347-8d90-749c30703bc4.png)
`tutorial.cxx`:

![image](https://user-images.githubusercontent.com/46334090/174336336-7af8f574-a6f8-46dd-85ef-7058f145751c.png)
`CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174336396-03e93661-6db2-41f2-ac6e-ba8306fcb6b7.png)

#### Step 2
Console Output

![image](https://user-images.githubusercontent.com/46334090/174335918-b8fc47d0-e49f-43e2-bb1e-a228991b44df.png)
`tutorial.cxx`:

![image](https://user-images.githubusercontent.com/46334090/174336127-5145a113-59c4-46f7-8b1a-846c50915325.png)
`CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174336218-4be139ec-90a6-449a-a8fd-04d10d25ebca.png)

#### Step 3
Console Output:

![image](https://user-images.githubusercontent.com/46334090/174337137-309b9ec5-0681-4597-8d4e-05ce0e25532d.png)
`CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174337225-cfa433ec-628f-4b1f-b5d3-bd39048497a8.png)
`MathFunctions/CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174337309-ef8edcdd-18d4-45e3-843c-a23024be05a8.png)

#### Step 4
Partial output for `ctest -VV`:

![image](https://user-images.githubusercontent.com/46334090/174339694-f6456df7-c36e-4e3f-bcb8-c7f047019f8a.png)

`CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174339835-51e18437-3446-43a9-a088-c717b75d660f.png)

`MathFunctions/CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174339895-973ecbe2-23a2-4ba1-90d7-f88244edabf1.png)

#### Step 5
Console output:

![image](https://user-images.githubusercontent.com/46334090/174445493-13af1b86-63aa-455d-93d0-6d91260a4a4e.png)


`CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174445602-b51bd3b9-5441-4521-9901-8dee45601e71.png)


`MathFunctions/CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174445620-d33892a6-7be9-421a-bf15-21a6c17e9ac9.png)

### Part 2
Makefile:

![image](https://user-images.githubusercontent.com/46334090/174676653-4e543f4a-48a0-49ca-b9f9-f445f42d65e6.png)

Sizes of shared and static versions (Makefile):

![image](https://user-images.githubusercontent.com/46334090/174676631-84f0cd18-1a3c-4de8-bb7b-7281b80d0ed7.png)
`dynamiclib`'s size is 16696, `staticlib`'s size is 16856.

`CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174688478-af91b965-01f2-49d2-87e3-0501349cbafe.png)

`source/CMakeLists.txt`:

![image](https://user-images.githubusercontent.com/46334090/174688491-4b5a5162-9e5b-41b7-bb99-1bb106ee313d.png)

Sizes of shared and static versions (CMake):

![image](https://user-images.githubusercontent.com/46334090/174688538-610c6cfd-72af-40af-bf2a-9ed8945ac3b4.png)
`SharedExecutable`'s size is 16696, `StaticExecutable`'s size is 16856.
