# AndroidStudio
Nume:NotitePacurar;
Autor: Pacurar Ioan Marius;
Descriere: Este o aplicatie in care utilizatorul isi poate salva diferite notite;
Sistem:Aplicatia are nevoie de android 4.1 pentru a functiona;
Biblioteca externa: am folosit implementation 'com.google.code.gson:gson:2.8.6';
In ceea ce priveste molidatea de rulare, codul care este scris in doInBackground se executa pe alt thread si onPostExcute trece pe main thread pentru a putea face update la UI. Doar de pe main thread se poate face update la ui, in taskul de get, se ia din shared si se tranfroma in lista, in cel de save, se ia lista se adauga elementul curent se salveaza. In onPostExcute se trimte catre UI rezultatul, prin acel listener ;

![]https://github.com/pacurarm/AndroidStudio/blob/master/imagine.jpg}
