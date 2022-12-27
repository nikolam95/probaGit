Osnovni tok git-a

working directorium (WD) je direktorijum u kome se nalazi .git i sve u tom direktorijumu. Staging area (SA) je sve ono sto se doda naredbom
	git add ., tacnije sve sto se prebaci iz WD ovom komandom. SA se nalazi .git folderu i ona je transparentna. Sve ono sto se nalazi SA
	jos uvek nije komitovano, da bi to bilo komitovano, potrebno je pozvati komandu git commit -m "Komit". Sada kada je pozvana ova komanda
	sav sadrzaj iz SA se prebacio u Local Repository (LR). Jos uvek sadrzaj nije postavljen na internet, a za to je potrebno da se sadrzaj iz
	LR prebaci u Remote Repository (RR) i to komandom git push