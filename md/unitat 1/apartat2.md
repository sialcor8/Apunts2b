# **Àlgebra de Boole**


## *Definicions.*

Partim d'un conjunt **$E$**,espai mostral o conjunt complet(en probabilitat s'anomena **succés segur**). Aquest conjunt està format pels successos elementals, **$E$**= {$E_1,E_2,...E_n$}.  
Per exemple, al llaçar una dau, els successos elementals possibles són els del succés segur **$E$**= {1,2,3,4,5,6}.

![**Cares del dau**](imatges/Figura%201.%20Cares%20del%20dau.png)

**Successos elementals d'un dau **$E$**= {1,2,3,4,5,6}.**  
Per tant, podem definir un succés com tot aquell subconjunt d'**$E$**,es adir tot, conjunt format per elements d'**$E$**. Es solen denotar amb lletres majuscules **(A,B,C...)**. Alguns exemples del llançament del dau: **A**="ix un valor parell"={2,4,6}; **B**="nombre primer"={2,3,5}; **C**="nombre menor o igual que 4"={1,2,3,4}.
**Succés impossible o conjunt buit**: és el conjunt que no té ningun element, és impossible que ocòrrega. Es denota pel símbol $\phi$.
Potència d'**$E$**, $\Omega$=**P(E)**: és el conjunt format per tots els possibles subconjunts o successos d'**$E$**, incluits el conjunt buit i el propi **$E$**. Vegem el conjunt potència de llançar una moneda (C=cara X=cruz)     $\Omega$=**P(E)**= {$\phi$,(C),(X),E=(C,X)}.

## *Operacions.Tipus de successos*

Siguen els successos **A,B$\in$P(E)** definim les següents operacions:  
- **Unió de successos**: la unió de dos successos **A $\cup$ B** la intersecció de dos successos **A $\cap$ B**és el succés format per tots els successos elementals comuns i no comuns a **A i B**.  
  ![**Unió**](imatges/Figura%202.1-Unió%20conjunts.png)
   **Figura 2.1**  
- **Intersecció de successos**: és el succés format pels successos elementals comuns a **A i B**.  
  ![**Intersecció**](imatges/Figura%202.2-Intersecció%20conjunts%20A%20i%20B%20(A%20i%20B%20compatibles).png)
  **Figura 2.2**  
- **Succés contrari o complementari**: el succés contrai al succés **A**, es denota **$A^c$** o **Ā**.  
  ![**Succés contrari**](imatges/Figura%202.3-Contrari.png)
  **Figura 2.3**  
- **Diferència de successos**: la diferència de de successos **A-B** és el conjunt d'elements d'**A** que no estan en **B** o a l'inrevés.  
  ![Diferència](imatges/Figura%202.4.1-Diferència%20de%20conjunts%20A-B.png)
  **Figura 2.4.1**  
  ![Diferencia2](imatges/Figura%202.4.2-Diferència%20de%20conjunts.png)
  **Figura 2.4.2**  
- **Successos incompatibles**: són aquells que no poden ocòrrer mai a la vegada i per tant **A $\cap$B**=$\phi$  
  Per exemple: **A**="parell"={2,4,6} i **B**={1,3}.  
  ![incompatibles](imatges/Figura%203.%20Successos%20incompatibles.png)
  **Figura 3:Successos incompatibles**  
- **Succés inclòs**: un succés **A** està inclòs en **B** i es denota **A**$\subset$**B**.Per exemple:**A**={2,3};**B**={2,3,5}.  
**Exemple 1**: Siguen **A**="parell"={2,4,6} i **B**="menor que 4"={1,2,3}:  
- **A $\cup$ B**={1,2,3,4,5,6}.
- **A $\cap$ B**= {2}.
- **$A^c$**={1,3,5} ; **B$^c$**={4,5,6}.
- **A-B**={4,6}; **B-A**={1,3}.  
**Exemple 2**: Siga **E**={1,2,3,4,5,6,7,8}; **A**={1,2,3,4} i **B**={4,5,6,7,8},resolem aquest exemple utilitzant **diagrames de Venn.**  
![Diagrames de Venn](imatges/Figura%204.-Diagrames%20de%20Venn1.png)  
 **Figura 4**:**Diagrames de Venn.**  
 >  Aci vos deixe l'enllaç a la web de l'autor d'aquesta imatge: [web de Jose Luis Lorente](http://www.joseluislorente.es/3eso/probabilidad/3_operaciones_con_sucesos.html)
>  *Per repassar la teoria de conjunts* [**clik aci**](https://www.disfrutalasmatematicas.com/conjuntos/venn-diagramas.html)  

## *Propietats de l'àlgebra de Boole.*

|                           |             **Unió**             |          **Intersecció**          |
| ------------------------- | :--------------------------------------: | :--------------------------------------: |
| **Commutativa**     |            **AUB=BUA**            |           **A∩B=B∩A**           |
| **Absorvent**       |             **AUE=E**             |            **A∩Φ=Φ**            |
| **Element neutre**  |             **AUΦ=A**             |             **A∩E=A**             |
| **Distributiva**    |     **AU(B∩C)=(AUB)∩(AUC)**     |     **A∩(BUC)=(A∩B)U(A∩C)**     |
| **Lleis de Morgan** | **(AUB)$^c$ = A$^c$∩B$^c$** | **(A∩B)$^c$ = A$^c$UB$^c$** |

>  **Altra propietat:(A$^c$)$^c$=A**

![](imatges/filatragaperres.jpg)

**ACTIVITATS D'OPERACIONS AMB SUCCCESSOS**

1. Escriu l’espai de successos S associat a l’experiment
   aleatori E: «llançar una moneda a l’aire»

2. Utilitzant nombres combinatoris, demostra que el nombre de successos associats a un experiment aleatori de
   3, 4 i n elements és, respectivament, 8, 16 i 2$^n$.

3. Es consideren els successos A: «obtenir un nombre primer» i B: «obtenir un nombre més petit que 10» de
   l’experiment aleatori E: «treure una bola d’una urna
   amb 20 boles numerades de l’1 al 20».Defineix A i B per extensió.

4. Demostra que A - B i B - A constitueixen successos
   incompatibles.

5. Justifica mitjançant diagrames les igualtats següents:a) A-B = A-A$\cap$B) = A$\cap$B$^c$b) B-A = B-A$\cap$B) = A$^c$$\cap$B

6. Demostra gràficament les lleis de Morgan de les operacions amb successos.

7. Si A i B són dos successos tals que A$\subset$B, justifica que:  
   a) A$\cap$B=A  
   b) A$\cup$B=B  
   c) $B^c$$\subset$$A^c$  
   d) $A^c$$\cup$B=$\Omega$e) A$\cap$B$^c$=$\phi$

8. En l’experiment aleatori E: «llançar dos dardells a la diana», considerem els successos A: «fa diana amb el primer» i B «fa diana amb el segon». Expressa en funció de A i B els successos:
   a) Fa diana amb el primer però no amb el segon.
   b) Fa diana amb algun dels dos.
   c) Falla els dos.
   d) Fa diana només amb un.  


Abans de començar a vore els diferents mètodes de calcular la probabilitat d'un succés, definirem la funció de probabilitat, que la qual li assignem la lletra **P** i les seues propietats:

> **P**: $\Omega$ $\to$ \[0,1]
>
  > **A** $\to$ **P**(**A**)

Propietats que definixen l'espai probabilístic ($\Omega$,**P**) i que ha de complir la funció de probabilitat:

1. 0≤**P**(**A**)≤1  (**P**(**$\phi$**)=0, succés impossible i **P**(**E**)=1, succés segur).
2. **P(A$\cup$B)**=**P**(**A**)+**P**(**B**)-**P(A$\cap$B)**
3. Si **A** i **B** són incompatibles $\to$(**A $\cap$B**=$\phi$):**P(A$\cup$B)**=**P**(**A**)+**P**(**B**).
