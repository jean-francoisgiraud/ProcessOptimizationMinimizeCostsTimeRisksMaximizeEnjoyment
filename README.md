# ProcessOptimizationMinimizeCostsTimeRisksMaximizeEnjoyment
Commutes LL (process optimization (minimizeTimeRisks maximizeEnjoyment))

Commute optimization

Commutes LL (process optimization (minimizeTimeRisks maximizeEnjoyment))
Baselines: (no traffic) 35kms 40min
General LLs: moto nc700s has best suspension and resistance to bad roads potholes

Commutes Acronyms: 
DatYMD date yymmdd; 
CT commute time in minutes;
ECT gmaps estimated commute time (mECT(median)  iECT(min) xECT(max)) 
D= day of week (m t w h f); 
TODe time of departure; TOAr time of arrival; TL (minutes) time lost in traffic (actual time -30); 
Hi= highways (y,n)
Way= roads bridges taken (JC, V) taken, WE weather (sun rain snow); 
Ways: 
- Bridges : JC Jacques cartier; VB=Victoria; CH Champlain 
- Roads : coV cote virtue, stC stCroix, avP avenue du Parc, Pap papineau, 138 sherbrooke, 

LLs: 
180815 optimum TOD (least red) is 1500. 1800 has much more red.
IF TOD office <1500 or >1800 THEN ECT 60min ELSE ECT 120min
IF TOD home <0500 THEN ECT 40min ELSE IF <0530<0600 ECT >60min
Avoiding higways at 1500 adds 30 min to CT.
HB Papineau JCmay be best option during rush hour. 
JC better than V in am no train. 
NO JTalon ReneL btw 16-18. 
LeaveCoV-ASAP lacadie-jams. 
Dont take Victoria Street Lachine  

Actual
DatYMD, _CT, TODe, TOAr, TL, Way 
180815, 060, 1500, 1600, 20, 13s20eJCwDetour
180815, 040, 0500, 0540, 00, JC.15.40
180814, 100, 1610, 1750, 60, coVbeginThimmensMarcelLPoirObrianJTavParcReneL, 
180814, 050, 0530, 0620, 10, V stPat 13   
180813, 080, 1700, 1820, 40, coV Pap JC 
180808, 120, 1500, 1700, 80, mteLiesseS 55 VictoriaSt VB
180807, 120, 1500, 1700, 80, 13s20eVB 

Google Maps estimates (in my experience the true CT exceed or are much closer to the xECT than even the mECT)
DatYMD, mECT, iECT, xECT, TODe, eTOA, Hi, Way 
180815, 0060, 0035, 0085, 1500, 1600, y, 40e15s20eJC
180815, 0065, 0040, 0090, 1600, 1705, y, 40e15s20eJC
180815, 0065, 0045, 0085, 1700, 1805, y, 40e15s20eJC
180815, 0050, 0035, 0065, 1800, 1850, y, 40e15s20eJC
180815, 0085, 0050, 0120, 1500, 1625, n, 40e15sChCoStLucGuyStJacqEdeLaMontVB
180815, 0095, 0050, 0140, 1500, 1635, n, 40eChRocklandAvVanHornePap
180815, 0090, 0055, 0120, 1700, 1830, n, 40eChRocklandAvVanHornePap
180815, 0090, 0055, 0120, 1700, 1830, n, 40e15sChCoStLucGuyStJacqEdeLaMontVB
180815, 0090, 0055, 0120, 1700, 1830, n, mteeLiesse55sRueVictoNotreDaVB
180815, 0100, 0060, 0140, 1700, 1820, n, HB Pap JC

