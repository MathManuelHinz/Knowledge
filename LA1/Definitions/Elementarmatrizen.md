# Elementarmatrizen #La1 
Sei $E_{ij}^{m,n}=(\delta_{ki}\cdot\delta_{lj})_{1\leq k\leq m| 1\leq l\leq n}$. Nun sind folgende Matrizen Elementarmatrizen, welche bei Multiplikation von links auf Zeilen und bei Multiplikation von rechts auf Spalten einfluss nehmen.
## Vertauschung
$L_{ij}^{(m)}=I_m-E_{ii}^{m,m}-E_{jj}^{m,m}+E_{ij}^{m,m}+E_{ji}^{m,m}$ vertauscht bei Multiplikation Zeilen/Spalten.
## Addition
$S_{ij}^{(m)}=I_m+\lambda\cdot E_{i,j}^{(m,m)}$ addiert das $\lambda$-fache von Zeile j zu Zeile i / das $\lambda$-fache von Spalte i zu Spalte j. #check
## Multiplikation
$E_{i}^{(m)}(\lambda)=I_m+(\lambda-1)\cdot E_{i,j}^{(m,m)}$ multiplizeirt die Zeile / Spalte i mit $\lambda$.