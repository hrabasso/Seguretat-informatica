# SMX2B

**Hector Rabasso Lopez**
[alu.hector.rabasso@mataro.epiaedu.cat](mailto:alu.hector.rabasso@mataro.epiaedu.cat)

# T02: Selecció d’un SAI

## 1. Introducció

TecnoGestió S.L. és una petita empresa de gestió documental i assessorament informàtic que disposa de quatre ordinadors de sobretaula, una impressora multifunció i un router d’accés a Internet. Com que es produeixen incidències en el subministrament elèctric, es necessita un SAI que protegeixi els equips essencials i permeti guardar la feina i apagar els ordinadors de manera segura.

Per adaptar l'estudi als requisits de l'activitat, s'han utilitzat equips reals, s'han indicat els valors de consum en W i VA, s'han comparat tres models de SAI amb els seus preus i distribuïdors i, finalment, s'ha seleccionat el model més adequat.

## 2. Inventari dels equips

Per representar l'equipament de l'empresa s'utilitzen models reals. En el cas dels ordinadors, la dada de 240 W correspon a la potència màxima de la font d'alimentació del model HP Pro SFF 400 G9.

| **Dispositiu**         | **Marca i model**   | **Quantitat** |  **W considerats** | **VA considerats** | **Al SAI?** |
| ---------------------- | ------------------- | ------------: | -----------------: | -----------------: | ----------- |
| Ordinador              | HP Pro SFF 400 G9   |             4 |           240 W/u. |          300 VA/u. | Sí          |
| Router                 | TP-Link Archer C6   |             1 |               12 W |              15 VA | Sí          |
| Impressora multifunció | Brother MFC-L2800DW |             1 | 470 W en impressió |             588 VA | No          |

### Impressora multifunció

La Brother MFC-L2800DW pot arribar a consumir 470 W durant la impressió. Connectar-la al SAI augmentaria molt la càrrega i reduiria l'autonomia disponible per als ordinadors.

Per aquest motiu, la impressora no es connectarà al SAI i es connectarà a una presa amb protecció contra sobretensions.

## 3. Càlcul de la potència necessària

### 3.1. Potència dels equips protegits

Els equips que es connectaran al SAI són els quatre ordinadors i el router.

**4 ordinadors:**

4 × 240 W = **960 W**

**Router:**

1 × 12 W = **12 W**

**Consum total connectat al SAI:**

960 W + 12 W = **972 W**

### 3.2. Marge de seguretat del 20 %

Per garantir que el SAI pugui treballar amb marge su
