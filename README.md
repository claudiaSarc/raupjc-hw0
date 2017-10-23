#Pitanje {1}
{
  Nakon dodavanja reference u folderu "Debug" pojavila su se dva filea - "ClassLibrary1.dll" i "ClassLibrary.pdb".
  Brisanjem .dll filea izvršni program se, naravno, ne može pokrenuti.
  S obzirom da se brisanjem ostalih fileova program normalno mogao pokrenuti, dovoljno je poslati izvršni .exe 
  program i .dll file.
}

#Pitanje {2}
{
  Nakon promjene aplikacija je ispisala novi string. Logično, s obzirom da će se automatski buildati sa "najsvježijim
  podacima". 
}

#Pitanje {3}
{
  Nakon dodavanja NuGet paketa, a zatim brisanja direktorija NodaTime nije se desilo apsolutno ništa, odnosno buildalo
  se sasvim normalno.
  Direktorij packages je "vratio" paket NodaTime.
}
