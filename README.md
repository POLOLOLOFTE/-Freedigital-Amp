# -Freedigital-Amp

a full analogic amplificator 2.1, built around tda2030. very Open Source!!! so everyone can make it like they want!!
For Half Life (Hackclub)

i have do it because i love music and i got some "great" speakers recycled from the trash, and i would rather make my own amplificator than let some multibilionare company do it for me and not get the best... btw i don't think that mine is better than some product made from years of reserch. but it's my amp! and all the work that i put it on it's all worth it!

the audio from a standard jack comes in and it goes trough some componets to introduce it to 3 tda2030 (the main amplificator process) they are three so one is for the right signal one if for the left and the third is for the subwoofer.
it's designed on a small foarm 100x100mm custom pcb and the tda2030 need passive cooling even if they have a thermal shut down emergency mode.
(the wireing digramm is nota thing to explain on a simple text(it's harder with my broken english) so this is how i'm going to explain it, sorry)

## INPUT:
it work with one jack from a phone/computer and 16 volt from a powersupply aon 3-4 amps.

## OUTPUT:
there are three screw clamp (other than the audio) or spring clamp on the rear where you put the positive and negative of the speakers... remember the speakers shouldn't more than 50w 8ohms each

## SETTINGS:
there are three potenziometers for each tda2030 so you can control endidually the left, right and subwoofer audio

### Extra Note:
The pcb isn'perfect there can be some static noise from the circuit and it's not made for staying 24/7 powered at 100% of volume

## Assembly
as materials you need what is in the bom on the bottom on the readme:

- you have to soder on the pcb all the components(you need soder and a iron); whaching the schematic(at the end of the readme)
- then you are good to go! just power the board from the screw connector neat the jack
- hook up some speakers and a subwoofer(opsional)
- put in the jack (from a phone/computer)
- enjoy the music

 # **IMPORTANT**

 ** The pcb is UNTESTED so it can blew up for something wrong do NOT fully thrust the system so much,
 I am NOT rensponsible if it blow up CAPACITORS ot TDA2030s **

<img width="567" height="557" alt="Screenshot 2026-10-16 181143" src="https://github.com/user-attachments/assets/ffa974b5-e071-4e65-8fea-99d9b6d0ac7d" />

<img width="562" height="546" alt="Screenshot 2026-10-16 180414" src="https://github.com/user-attachments/assets/37fb3b2d-e78e-40dc-a61d-dd7f1cc6056d" />

<img width="1074" height="875" alt="Screenshot 2026-10-11 110512" src="https://github.com/user-attachments/assets/cf056830-d130-4135-bc88-f4818dc7755c" />

<img width="794" height="510" alt="Screenshot 2026-10-27 153004" src="https://github.com/user-attachments/assets/dd07092d-e181-4e8c-b819-f1efb8db7ac9" />

<img width="871" height="457" alt="Screenshot 2026-10-27 153016" src="https://github.com/user-attachments/assets/72ab0a9b-7dfc-4cd7-ab41-db3c853a78fe" />

<img width="766" height="415" alt="Screenshot 2026-10-27 153032" src="https://github.com/user-attachments/assets/f0262f48-8298-4d61-97ea-cadf4644e3f0" />



| Item Name | Qty | Price (total) (USD) | Item link | Notes |
| --- | --- | --- | --- | --- |
| TDA2030 | 3 | $6.69 | https://www.amazon.it/-/en/gp/product/B07CJY4255/ref=ox_sc_act_title_8?smid=AXQNTRGL896M5&psc=1 | The main chip |
| 1N4001 | 6 | $8.96 | https://www.amazon.it/AUKENIEN-Pieces-Rectifier-Electronic-Silicone/dp/B08Y8KLFWW/ref=sxin_10_pa_sp_search_thematic_sspa?content-id=amzn1.sym.f05bb22c-b10e-43e7-b840-674903c7db32%3Aamzn1.sym.f05bb22c-b10e-43e7-b840-674903c7db32&crid=2FYDE8PDXCJSS&cv_ct_cx=1n4001&keywords=1n4001&pd_rd_i=B08Y8KLFWW&pd_rd_r=f538e61c-1c49-43fd-99dc-07afb98a1078&pd_rd_w=2Y1jS&pd_rd_wg=5yTNH&pf_rd_p=f05bb22c-b10e-43e7-b840-674903c7db32&pf_rd_r=GJRGVC585KR0FBXZC48R&qid=1792769780&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=1n4001%2Caps%2C182&sr=1-2-50840d04-82cc-4adf-b6cc-9f330c77868e-spons&aref=z7QERglYFX&sp_csd=d2lkZ2V0TmFtZT1zcF9zZWFyY2hfdGhlbWF0aWM&psc=1 | you can get 200 for 9 dollars |
| resistor 10k | 2 | $15.69 | https://www.amazon.it/-/en/gp/product/B0FP51H3ML/ref=ox_sc_act_title_1?smid=A2X2IS1I8BHRL9&psc=1 | you can get all of them once |
| resistor 100k | 6 | | | get this in a kit |
| resistor 22k | 3 | | | get this in a kit |
| resistor 680Ω | 3 | | | get this in a kit |
| resistor 1Ω | 3 | | | get this in a kit |
| resistor 10Ω 5W | 1 | $16.25 | https://www.amazon.it/-/en/Innfeeltech-Tolerance-Resistor-Projects-Experiments/dp/B0FG25S9BR/ref=sr_1_7?crid=1B0NPLK2B32TC&dib=eyJ2IjoiMSJ9.Scs8-FuewxLpGOpdGYz0p2tV7cUOCUX3GF4mUKxI1DU6NA7-bN_V4clB0l8TXbvCzyKTaMt7hNnqy144VDAkcVWwwOL5zHRgJeIZP5KMo7o2mDFh1wKYmf8kLG0Ex5gra7KmvPm2B27ffWNTpQ7EHBUOGSfsWj7aaAMh_Ib9G6LY1fFMWFBnrSwezEhFxQ-VS8OXPOCDQgXI3IvHK9Ex_7MSvVvFpufJz9n3aWbGZEp9M5V6lziDasb1AsIVlXLdFRg1TSwQ5UKuXucKiTjfUnr0hortJ1ijx7xrTfaXo9w.l0t8KEW1TYORQRVuwqhuOfhoq3YdMGw8-xbfqjIcLOk&dib_tag=se&keywords=10homs+5w+resistor&qid=1792770093&s=industrial&sprefix=10homs+5w+resisto%2Cindustrial%2C120&sr=1-7 | the ceramic one |
| copper wire 0.8-1mm | 10-12 turns | $14.57 | https://www.amazon.it/-/en/gp/product/B0CS8V42H3/ref=ox_sc_act_title_6?smid=A1LK21T5CK0Y8M&psc=1 | to wrap it around the ceramic resistor |
| condensator 10uf 25V | 3 | $7.29 | https://www.amazon.it/-/en/Aluminum-Electrolytic-Capacitor-25V-Microwave/dp/B0FDPWGWWJ/ref=sr_1_9?crid=C5BOM4U6KYXF&dib=eyJ2IjoiMSJ9.LSiuYq2FCh0egSiZCVXBDgtqf9YRCTDODsGoj1gyV6TElrz6s4esagkWBgiefzRJAuGFnkvvwxGyJs2YDObtWuDjz7T60MvbGR_hxPi1jN4JcUpgRRN37HkW_qJ7sHODQNGvibzaGK_W4DFvwFPmyR_azW77qsArORLo2YgN_yHKFh-rWc43EsYec8otTvvkiasBQ4wfymVjEPNe2Xu7K-jK0HUUxnrVwYNTO_mvWvFf-mO4lEYdYTu0oAr5MqE4Ytclr2J4mcEDzkZXTj1AB3bC-yykBzvX1E1-0aRBpWY.zjHfs2OkTKXnMhnPGOdG_Vhhd5duc5kQ1GFVzTE5KIA&dib_tag=se&keywords=condensatore+10uf+25v&qid=1792770669&s=industrial&sprefix=condensatore+10uf+25v%2Cindustrial%2C126&sr=1-9 | |
| condensator 22uf 25V | 3 | $8.30 | https://www.amazon.it/-/en/QUARKZMAN-Electrolytic-Capacitor-Aluminium-Capacitors/dp/B0G56FWVGX/ref=sr_1_4?crid=T98MPAVDTA2Z&dib=eyJ2IjoiMSJ9.L_odFOx6XBQYejsZhqHLbnYJxT4VA790aNziTO0ag_o-CVstSlUV35lNNkYwe-fO3bMDnziuRYyJuWM2jBvAMqZUBNnOFOOESn_EPpkrTYIA09VNIGPmrbc94JB8liU2UyafeMaqphUhBk9qcQLDEmi-FqVWOQuaHnjy-VhnsRfsSmXaV4dCGTpwh7yIWWF5B4fav4ixdl-6k6JYpeGj6UAGbZV6O4xUirx0J722WVyTDwP4kWF-R-4ltd0emhUx1L3Eio61yE1LcZXQkPZDR4xFHuVjhCGLoxXnODxKEfU.3vi3UqI9uoCa8QOpzKgGD75RI-VM42V7wuLpVwEScnM&dib_tag=se&keywords=condensatore+22uf+25v&qid=1792770738&s=industrial&sprefix=condensatore+22uf+25v%2Cindustrial%2C115&sr=1-4 | |
| condensator 2200uf 25V | 4 | $8.54 | https://amazon.it | |
| condensator 100nf | 6 | $11.13 | https://www.amazon.it/-/en/Multilayer-Monolithic-Capacitors-Different-Electronic/dp/B0GWMVTD1H/ref=sr_1_10?crid=2IVX3RRIZURSU&dib=eyJ2IjoiMSJ9.n1xKTGmbGyA-2SUZmJkTlhj1pfeyEPUzMORMi8h4CCsmk1a1i4k1xN8dUSgnCa3tQPm358qEAAEQ15NSxepj8qwEqLJszSWEWAr8j5-X6zElzeAEmQn1wj4tCrYmazUmn8kNuconuhvtxebJ3uRPUeMi3Bpui8cRIXso5xAqH3-Zg78oxSXLCUVnQsAxmTLCFKPjzCgq9VVdLLTMSbLgNN2Nr9kvSZdmANI6LPrSGo6t628Emrm6LWSAnCX1pR8c32nfPsRIbP8kALbTqat1lqTiQ1UdbWS1oLH6qRDOOlU.RXlpA9rYWzoFDd-YUg6GLDR6kHqAqU8k40__FQYSrNg&dib_tag=se&keywords=condensatore+104&qid=1792770951&s=industrial&sprefix=condensatore+104%2Cindustrial%2C124&sr=1-10 | |
| condensator 220nf | 3 | $16.82 | https://www.amazon.it/CBB81-1000V-Polypropylene-Capacitor-Voltage/dp/B0DCFXJFJM/ref=sr_1_13_sspa?crid=3J1ZVXC4BB3I7&dib=eyJ2IjoiMSJ9.jo-a6Ciacp2sMADAmsIOFcdenbnVn-4VdGcrCjea3hOtvWWpXNY71hP0WcLw4umcaz2ZxhqXUrmedS1rc9FUGeao73UcibcFCBHOvopEnppHOCEWVuT6uCkoiccAhFUC5-rhIIr4KjcS7k_ZlzaBkVn9vCaSdD0OP4urf7HGmUHy9SY-ymL3IKlmf9onsAbCTgWG7RwChiAQ6LVTx0HpcHZp8Yf9NLepB1lkEjijMY70AITAFYhDGnwkSJH6Nl3fhYweobUhyw8oSV44EQe9gTrR_KR4KuGUR_DbNE-mTJM.2CRdwFxtc0T46XKF9F-Ga5nRPtz1mBHe0kxWrt8LJio&dib_tag=se&keywords=condensatore+220nf&qid=1792771250&s=industrial&sprefix=condensatore+220nf%2Cindustrial%2C125&sr=1-13-spons&aref=tX19d3y0Os&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&psc=1 | |
| 10k potenziometer | 3 | $11.20 | https://www.amazon.it/-/en/RUNCCI-YUN-Terminal-Rotary-Potentiometer-Linear/dp/B07RHJZ979/ref=sr_1_7?crid=21ICWWCGYB47L&dib=eyJ2IjoiMSJ9.CiF77j-BQNJ4ELBIJbrLTxFxpHBgf2ZDOHHu2dMKAQv_OqEwOZhciXMFus_fFrV6MJJrFIxIJzSyazEZtxOnNPYMBW44sJYdX5zu6exgKgplnSsKDzo9yYdNiAP2LPL3VNkwpEUikDPUvRI-s46rGfOx3ksRKzOsUKgzUfTjY8pA0sGaYYu5HWuNkid3oSmawHv867Y1tGr24BIbT3NmuhNl56rc0qJZ4AxU618JSVTm_Ikm11hWA39cMWUDXyympY6SD8PKnhr9aBR3rqEe1HDKibaygzQ4RiVotVpDtjI.CWnLL06XeDyoejRoiuHzGrOZsavvX4bzLuTi4I2dUkY&dib_tag=se&keywords=10k%2Bpotentiometer&qid=1792771074&sprefix=10k%2Bpotentiometer%2Caps%2C157&sr=8-7&th=1 | |
| one 3.5mm jack input | 1 | $8.86 | https://www.amazon.it/-/en/3-5mm-Female-Stereo-Jack-Disconnect/dp/B0868TM4FC/ref=sr_1_18?crid=3CDLKFXA0JAAQ&dib=eyJ2IjoiMSJ9.wjOHOwoahBhJfJiL1YiRXxd8mS7PK7O5BqYpGmYIO_Ry6CkByLdsht2toxIKSCyUu8hlNAH8Vjbdxk2XPODj5tYiMD70uTLDZQkX8fYuzc3jXrxdIbplqkGgnuuV5B_uSlYVPkaNkTVNM5Y6b74yvfiF5JZ67hNufQDMiOFBL3WNoFw2yBZZGTlsuKwYb8HylG8KO7wmFy2sJZKNmsJuE0rwiZAftr_7XPnEx77ET6UZWcqcy7xm-SbJbFKj-8UVqA1F9sVHBKWREKkzrTjUUVrLG3uTcVi_JwmZA5EbSBM.rp3jBQOJ1NRV5HjDUlxTJFbqKY1S91YfKkDw7e8B85Y&dib_tag=se&keywords=jack+input+3.5mm+pcb&qid=1792785978&sprefix=jack+input+3.5mm+pcb%2Caps%2C125&sr=8-18 | the wide one |
| set of 1x2/1x3 screw terminals | 6 | $12.33 | https://www.amazon.it/-/en/gp/product/B0FN6VYSFN/ref=ox_sc_act_title_4?smid=A2KWOEY1RHRC64&psc=1 | you can use other tipe of compatible connector |
| the pcb itself | 1 | $4.00 | | the cost depends a lot |
| heat sink | 3 | $8.96 | https://www.amazon.it/gp/product/B0CSJVJ4CG/ref=ox_sc_act_title_3?smid=A2FXWI8CY4G34J&psc=1 | |
| Total Price (USD): | | $159.59 | | |


here is the list for pcb-components:

- [ ] U1, U2, U3		TDA2030	
  
- [ ] D1–D6		1N4001	(they are 6 and you can put similar diods in it)
  
- [ ] R1, R2		10k	sub low-pass filter

- [ ] R4, R5, R6, R7, R18, R19		100k	8V bias divider

- [ ] R14, R15, R16		22k	feedback

- [ ] R8, R9, R10		680Ω	pin 2 network

- [ ] R11, R12, R13		1Ω	output stability network



- [ ] R17		10Ω 5W	in parallel with L1

- [ ] L1  	1–2µH	turns wound on R17
 (for cost reason thoose two are thogheter... like you connect the resistor and then you run 10-12 spirals of copper wire)



- [ ] C1, C2, C3		10µF 25V	input coupling

- [ ] C5, C7, C8		22µF 25V	pin 2 network

- [ ] C4, C15, C16		2200µF 25V	output coupling

- [ ] C6	1	2200µF 25V	power supply reservoir

- [ ] C9, C10, C11		100nF	output stability network

- [ ] C12, C13, C14		100nF	supply decoupling at pin 5

- [ ] C17		220nF	sub filter

- [ ] RV1, RV2, RV3		10k potentiometer	volume-for each speaker

- [ ] J1		3.5mm audio jack	input

- [ ] J2, J3, J4		2-pin terminal block speakers

- [ ] J5		2-pin terminal block	16V power input

- [ ] J6		5-pin terminal block	test points

- [ ] then you need the custom pcb: you find it in the extra folder

- [ ] speakers 2 standard and 1 subwoofer: !MAX! 4ohms 50w

- [ ] and you probably need some heat sink: werever you have to stay cheap
