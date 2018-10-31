# ProcessOptimizationMinimizeCostsTimeRisksMaximizeEnjoyment
Commuting LL (Lessons Learned) (process optimization (minimizeTimeRisks maximizeEnjoyment)).  
Machine and deep learning on this data to determine and predict the best commute routes for varying TOD.  
Best TOD mtwt is 1545 f is 1430.  
Risks are lowered (maybe at CT expense) with time by the CI of always taking the same route.  
See below the data for definitions acronyms notes explanations.  

OPTIMUMS  
DayWeek, CT,  TODe, TOAr, TL, Way, LL  
mtwtf00, 040, 0430, 0510, 00, VB15n40w, before leaving listen to 730AM to know if 15n or JC are blocked  
mtw0000, 055, 1545, 1655, 15, cavendish520e15s(adds1k3minAferZENer)PeelDeLaComMills(adds1k1minZENer)VBvitoriaStreetJeannette116  
thfr000, 070, 1545, 1710, 30, 13s32s25sStPatWellingtonVB, only if 40e 15s 20e are badly blocked  

Actual  
DatYMD, CT,  TODe, TOAr, TL, Way, LL
181030, 090, 1615, 1735, 70, 40eCavendish520e15satwaterStJacquesDesSeigneursCentrewellintonE-VB 
180912, 090, 1605, 1735, 70, 13s32s25sStPatWellingtonVBosbornAlexandraChurchillEdouard,  
180917, 040, 0420, 0500, 00, jcB13n40e  
180914, 075, 1430, 1545, 30, 13s20eVB, Friday  
180912, 070, 1550, 1700, 30, 13s32s25sStPatWellingtonVBosbornAlexandraChurchillEdouard, very good for a thursday  
180912, 060, 1550, 1650, 20, 13s20eVBosbornAlexandraChurchillEdouard, wednesday  
180910, 050, 1545, 1635, 10, 13s20eVBosbornAlexandraChurchillEdouard, monday  
180907, 035, 0415, 0450, 00, VB15n40w  
180906, 060, 1545, 1645, 20, 13s20eVB, Thursday lost <10m at 13s20e and ~15m Well-W to VB  
180906, 035, 0415, 0450, 00, VB15n40w  
180831, 080, 1440, 1600, 40, 13s20eNdameFrontUturnReneJC (long wend)  
180830, 110, 1530, 1720, 70, 13s20eAtwaterStJacquesVinetSLionelGrouxWCharlevoixSWellingtonVB !NO!(vinetCharl=30m)  
180829, 070, 1540, 1650, 30, 13s20eAtwaterStJacquesVinetSLionelGrouxWCharlevoixSWellingtonVB  
180828, 110, 1500, 1650, 70, 13s32s25sSt-Patrick VB, when VB red but not too bad from st-patrick  
180824, 075, 1445, 1600, 25, 13s20eVB, Friday VB red but not too bad  
180821, 055, 1500, 1555, 15, 13s20eNdameFrontUturnReneJC  
180820, 035, 0420, 0455, 00, VB15n40w  
180820, 055, 1500, 1555, 15, 13s20eNdameFrontUturnReneJC  
180820, 035, 0420, 0455, 00, VB15n40w  
180817, 070, 1500, 1610, 30, 13s20eNdameFrontUturnReneJC (N-1)  
180817, 030, 0420, 0450, 00, VB15n40w  
180816, 070, 1500, 1610, 30, 13s20eDeLmaisoneuveJC  
180816, 030, 0430, 0500, 00, VB15n40w  
180815, 060, 1500, 1600, 20, 13s20eJCdeLreneL  
180815, 040, 0500, 0540, 00, JC.15.40  
180814, 100, 1610, 1750, 60, coVbeginThimmensMarcelLPoirObrianJTavParcRene  
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

Notes:  
N-1 Top congestion friday summer rain shortcuts saved 60min  
Commute optimization  
Commutes LL (process optimization (minimizeTimeRisks maximizeEnjoyment))  
Baselines: (no traffic) 35kms 40min  

Acronyms:  
DatYMD date yymmdd  
CT commute time in minutes  
ECT gmaps estimated commute time (mECT(median)  iECT(min) xECT(max))  
D= day of week (m t w h f)  
TODe time of departure; TOAr time of arrival; TL (minutes) time lost in traffic (actual time -30)  
Hi= highways (y,n)  
Bridges : JC Jacques cartier; VB=Victoria; CH Champlain  
Roads : coV cote virtue, stC stCroix, avP avenue du Parc, Pap papineau, 138 sherbrooke  
Way= roads bridges taken (JC, VB) taken, WE weather (sun rain snow)  
Highways (number-direction): 13-s 20-e 15-n 40-w  

Lessons Learned (LL):  
@16h delaysInMinutes(13-s:5 20-e:10 VBwell-w:15 VBpeelDeLaCmills:10)  
General LLs: moto nc700s has best suspension and resistance to bad roads potholes  
!no! Mercier may be the best fastest option  
180830 construction on des seigneurs st-patrick= vinet Lionel Charlevoix !!!NO! 30m toGetToStPatrick  
IF all red THEN 13-S 32av-S Victoria-E 25-S boulSt-Joseph-E  
180815 optimum TOD (least red) is 1500. 1800 has much more red.  
IF TOD office <1500 or >1800 THEN ECT 60min ELSE ECT 120min  
IF TOD home <0500 THEN ECT 40min ELSE IF <0530<0600 ECT >60min  
Avoiding higways at 1500 adds 30 min to CT.  
HB Papineau JCmay be best option during rush hour.   
JC better than V in am no train and 15n often closed at night for construction.  
NO JTalon ReneL btw 16-18.  
LeaveCoV-ASAP lacadie-jams.  
Dont take Victoria Street in Lachine (funnels).  
