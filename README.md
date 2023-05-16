# Proiect Cloud Computing
- Student Draghia Maria Cristiana 
- grupa 1119

In cadrul priectului am creat o aplicatie ce consta intr-o aplicatie care isi propune sa faciliteze gestionarea unui magazin de bijuterii. Aplicatia permite afisarea unui catalog de produse, fiecare articol avand informatii despre tipul de metal din care este confectionat si pretul acestuia.



- link video- prezentare proiect

- link publicare

## 1. Introducere
In cadrul priectului am creat o aplicatie ce consta intr-o aplicatie care isi propune sa faciliteze gestionarea unui magazin de bijuterii. Aplicatia permite afisarea unui catalog de produse, fiecare articol avand informatii despre tipul de metal din care este confectionat si pretul acestuia.

2.  Descriere problemă 
Aplicatia  este utila pentru ca are ca scop reducerea efortului de creaa un catalog al produselor pe care magazinul le furnizeaza in functie de caracteristicile acestora.

3. Descriere API 
Aplicatia foloseste o baza de date MongoDB pentru a-si stoca datele
![image](https://github.com/Cristiana24/proiect/assets/133686774/6b45b7de-c749-49c9-8f97-e13e6f21853b)

Baza de date este formata din urmatoarele obiecte 
![image](https://github.com/Cristiana24/proiect/assets/133686774/4d549d85-55df-4236-9229-ff46f4245d0a)

Toate aceste date sunt preluate si afisate astfel:
![image](https://github.com/Cristiana24/proiect/assets/133686774/0c65f487-9d59-4c57-833d-d33200caba8e)
In cadrul fiecarei retele este amplasat un butod Delete, care apelat, sterge inregistrarea efectuata 
Cod:
![image](https://github.com/Cristiana24/proiect/assets/133686774/0a8f8825-bb5d-43a8-bc64-7f75349784b5)

In cadrul paginii de insert https://proiect-cbdkaoqo5-cristiana24.vercel.app/insert se pot introduce date in box-urile aferente, iar dupa completarea lor, prin apelarea butonului de Adauga, se vor adauga caracteristicile produselor in pagina principala.
![image](https://github.com/Cristiana24/proiect/assets/133686774/b5565a56-2380-4144-ae62-46cff36d38fe)

Totodata aplicatia prezinta si o functionalitate de a cauta informatii despre bijuterii cu ajutorul OpenAI
![image](https://github.com/Cristiana24/proiect/assets/133686774/e4f4815b-3a3d-4d8d-84a3-3690ae75f174)


4. Flux de date 

Avem request uri de tip GET
![image](https://github.com/Cristiana24/proiect/assets/133686774/97d63692-9bee-4f23-983a-9d2e881431b3)

Totodata avem request uri de tip POST
![image](https://github.com/Cristiana24/proiect/assets/133686774/9acb39e1-b688-4d20-b7d4-4de86829d79c)

Si request uri de tip DELETE 
![image](https://github.com/Cristiana24/proiect/assets/133686774/2ce38ca6-83ae-45ff-b23a-c90081f924e4)


5. Capturi ecran aplicație 
Capturile de ecran au fost inserate la punctele anterioare

6. Referințe
https://github.com/guritaalexandru/cc-next-2
https://gurita-alexandru.gitbook.io/cloud-computing-2023-simpre/
