# [ Romhack (SNES) SD gundam G Next ] - Balance Patch

 ![GnxA](/image/a.png)

 ![GnxB](/image/b.png)

 ![GnxC](/image/c.png)

 ![GnxD](/image/d.png)

 ![GnxE](/image/e.png)

 
 
<br>

### v12r5 [13, Feb] - SP Ship's Ttc Space, 1st Ai Hack

- Added tactical physical space concept

  within the Supply Ship (3 Supply Points = 1 MS Slot)

- The first production of the SP Ship is empty

  in some spaces (different on each difficulty level)

- Solved the problem of one-sided TecView

- Improved of too often ship's production

  in the Early days of first Com AI (turns 2-7)

- Improvement of thread sync issues between

  SA1-CPU processors during MS control of Com AI

  (Delayed 50-60Hz cycles per each Ship)
<br>

- Many changed blc of SP Ships : Cost, 1stProd((Orig,Basic)/Full SP Points

      Columbus : 8000 C, (12, 15) / 18 SP

      Pazock :   7000 C, (13, 16) / 19 SP

      Medea :    5500 C, (15, 18) / 21 SP

      FatUncle : 5000 C, (15, 18) / 21 SP

      LVE Rose :

            37000 C, 48 MSp : 36 / 42 SP (Original)

            39000 C, 32 MSp : 45 / 48 SP (Basic)




<br>

### v10 [25, Jan] - Added new Tec status number

  Changed name format of MS : GP02 PHYSALIS

  And use the space left by it

- Additional balance of supply Ships.

- Columbus : 20 -> (12, 15) MA Supply Points (Orig, Basic)

- Pazock : 25 -> (16, 20) MA SPs (")

- Medea, FatUncle :

       20 -> (15, 20) MA SPs (Org, Basic)

       4000 -> 5000 Cost (Common)

- LVE Rose :

       40000 -> 37000 Cost (Original Only)

       48:36 -> 36:45 MS/MA SPs (Basic Only)

<br>


### v09 [15, Jan] - Terrain Information changed

   From Chinease Character -> Image Icon

- Additional balance adjustments
  
- Metas (1000) 1700 -> 1500 Cost ( Orig Basic common )

- GM III (123) 115 -> 117 Energy ( common )

- JamesGun 1400 -> 1300 C, 138 -> 135 En  (")

- GP03 Dendrobium +1 En (")

- GunEZ 1800 -> 1700 C (")

    144 -> 138 En (Only Origin difficulty)

<br>


### v08b [20, Dec] - A basic ver with slightly lower difficulty

- MS speed doubled in anti-ship battles

   ( Battle time (30) 10 -> 15 seconds )

- R79 Gundam Classic 1200 Cost Returned

- Rick Dias (900) 1500 -> 1300 C

- Methuss  (1000) 1700 -> 1500 C

- GM III    (700)  900 -> 800 C

- Gun EZ   (1800) 1800 -> 1700 C

  ( Other balance is the same as previous ver. )

<br>


#### v08 [19, Dec] - In addition to v07

- MS's dive speed in anti-ships battle is 3 times faster!

   ( Battle time reduced from 30 sec to 10 seconds )

<br>

### v07 [16, Dec] - Stabilized ver of the Previous v05

- Fixed No Gold fatal error when TecUp enough money.

- Moved code to safer area ( Does not damage the main Bg )

 <br>

 #### - Changes ( v03 v05 common )

- R79 Gundam - 1200 -> 1300 Cost

- GunCannon  - 1000 -> 1200 C

- GunTank    - 1000 -> 1100 C
 
- Nemo       - 108 -> 96 Energy (HP)

- Rick dias  - 900 -> 1500 C

- Metuss     - 1000 -> 1700 C

- GM III    - 700 -> 900 C, 123 -> 115 En

- Jegan      - 1400 -> 1200 C, 135 -> 127 En

- V-Gundam   - 144 -> 147 En

<br>

To normalize the easy difficulty and be faithful to

the historical accuracy. Nerfed the early MS and

increased the mid-game, specially the Jegan MS.

<br>

Although the early operation is difficult compared

To other factions, but the Gap will be filled with better

perf of the Earth Federation Army's long-range Units.

<br>

##### There're also low-level code modifications

- All MSs become Thanosed anti-ship attack power

- v03 : ( Attack + 2 ) ÷ 2

- V05 : ( Attack + 1 ) ÷ 2 + 1

<br>

##### Modding only for v05 !

- When press the Tec Up, the other factions also upgraded

 at a Certain rate. (Reflecting real case of Tech theft)

- Like 2/7 ratio, To resolve the maximum Initial TecLev of 20.

- Reflecting the tension of the TecUp together of old G or GX

- Rarely, the User's tech also increase double, like 1/7 ratio

- Beta ver Caution ! : If press Tec Up when enough money,

  Tec Up will cause a critical error !!

- Other common issue : Ugly tile patterns output on the main

  background screen, because some codes are allocated to the

  graphic area ( v05 look like Jiong? )

 <br>

### This Patch includes translations of the old English Ver.

 <br>


### Future update plan

- Reduced the battle time between ships 30 sec to 10-15 seconds [★]

- Replaced some terrain attribute font with thumb icons [●]

- Addtional translation of some UI [ ]

 <br>
 
### Applied ROM file name : SD Gundam G Next (Japan).sfc


  ---
