# KiCad Library
## A library of symbols and footprints used in Allen Synthesis modules
  
This library can be very easily added to your own KiCad library by following the instructions below.

### Adding the footprint library

1. Follow the [GitHub instructions](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) to clone this repository to your KiCad '3rdparty' folder. An example location for this folder is `C:\Users\username\Documents\KiCad\7.0\3rdparty\`. During the cloning process make sure you don't change the name of the repository as the 3D models will only be automatically linked if the folder name is `Allen-Synthesis-KiCad-Library`  
  
2. Ater cloning is complete, make sure your folders are arranged exactly as follows:
```
├── KiCad
│   ├── 7.0
│   │   ├── 3rdparty
|   |   |   ├── Allen-Synthesis-KiCad-Library
|   |   |   |   ├── 3dmodels
|   |   |   |   ├── allen-synthesis.pretty
|   |   |   |   ├── ...
```
3. Now open the KiCad footprint editor  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/3ffc1024-e2d1-4a9f-bbbe-23dc5996bba9)  
  
4. Click File -> Add Library  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/bdc19f50-1bb2-4888-8a2d-5b43ad3c5784)  
  
5. If you have a project open it will ask if you want to add the library globally or just for the project, select Global and click OK. If you don't have a project open, ignore this and skip to the next step  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/e55fd31a-a404-4016-9291-a5572def145a)
  
6. Navigate to the Allen-Synthesis-KiCad-Library folder, double click it, and click once on 'allen-synthesis.pretty', then click Select Folder  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/5c5c014b-e9ab-47c2-8258-85d6a54cf004)  
  
7. You should now see the components in the library on the left hand side of the footprint editor. The 3D models will have been automatically linked  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/ba6249de-c6d2-48f2-8e20-ae856c5ae176)

### Adding the symbol library

1. If you haven't already, follow steps 1 and 2 in [Adding the footprint library]() to clone this repository

2. Open the KiCad symbol editor  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/d7306712-2921-42f2-b113-202ea22fe6ee)  
  
3. Click File -> Add Library  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/b9f6b392-5819-4c6d-9d8c-696b2af17379)  
  
4. If you have a project open it will ask if you want to add the library globally or just for the project, select Global and click OK. If you don't have a project open, ignore this and skip to the next step  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/e55fd31a-a404-4016-9291-a5572def145a)
  
5. Navigate to the Allen-Synthesis-KiCad-Library folder, double click it, and click once on 'allen-synthesis.kicad_sym', then click Open  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/3cf5afd6-3236-4428-b55f-1f7cfc14a455)

6. You should now see the symbols in the library on the left hand side of the symbol editor  
  
![image](https://github.com/Allen-Synthesis/Allen-Synthesis-KiCad-Library/assets/79809962/db253494-b27c-466c-909e-0d2ca4493cb0)
