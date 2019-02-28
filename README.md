# Motor-Rad
The Ultimate Bike App
                         _
                       ,S/  .e.##ee
                     ,SS/_ /#####""
                   ,SSSSSS`|##|
                 ,'|SSSSSS/%##|
                 | ;SSSSS/%%%/ .-""-._                           __..ooo._.sSSSSSSSSS"7.
                 |/SSSSS/%%%/.'       `._ __               _.od888888888888"'  '"SSSSS"
             ___  `"SSS/%%%/"-.,sSSs._   8888o._    __.o888888888""SS""    `-._    `7Sb
      _.sssSSSSSSSSSSS/`%%/ ,sSSSSSSSSS-.888888888888888888888"'.S"         ,SSS""   `7b
   ,+""       ```""SS/%%./,sSSSSSSSS".   `"888888888888888"'.sSS"         ,SS"'        `S.
                    /%%%/sSSSSSSSS"   `s.   `"88888888"'.sSSSS"         ,S"'             7
                   /%%%/ `SSSSSSS$$,..sSS`-.   `"88'.sSSSSSSSS._     ,-'
                  /%%%/    `SSSS$$$$SSS",\\\`-.   `"SSSSSS"  8"""7.-'
                  /`%/      `SS$$$SSS,dP,s.\\//`-.   `SS" ,'`8       ,ee888888ee.
        ,oo8888oo/ /         `"""",d88Pd8888./,-'/`.  `,-._`d'    ,d88888888888888b.
     ,d888888888/ /8b.          d8888Pd8888888bd88b`.  :_._`8   ,888888"'    '""88888.
   ,888P'      / /"888b.       d88888`8888888Pd8888 :  :_`-.( ,d8888.__           7888b.
  d88P        / /   `788b     (88888:. `8888Pd88888 ;  ; `-._ 8888P_Z_.>-""--.._   `8888
 d88'     ,--/ /      `88b     `88888b`. `8P 78888";  ;      `"*88_,"   s88s.       `888b
d88'    ,',$/ /$$$$.   `88b      `8888b `. `"'88"_/_,'`-._         `-.d8"88"8P.      `888.
888    ; ,$$$$$$$$$'    888        `"8'   `---------------`-.._      8888888888       888'
888    : `$$$$$$$':     888                                 '888b`-._8s888888"P      .888'
788.   `  `$$$$'  ;     88P                                  8888.   "8878888P'      d888
 88b    `.  `"' ,'     d88'                                  '888b     '88s8"'     .d888'
 `88b.    `-..-'      d88'                                    '888b.             .dd888'
   788b.            ,888'                                       7888b._       _.d8888P
    `7888oo..__..oo888'                                          `"8888888888888888"'
      `"7888888888P"'                                               `"788 mGk 8P"'

This is the personal App for your bike.

This app will show data about your bike in the three following fields:
1) Distance covered by the bike
2) Fuel input
3) Bike Health

These fields will have extensive information of trips taken, the amout of fuelling done at said time and the device repair/service timings.

Apart from this, there is an option to calculate the mileage on a regular basis and provide real time information about how your bike's engine performs.

Interface:

   ,
.-/BA-.,::                                    
(_)'==(_)                               
    |                                    
    |____________________________________
                                        |
                                      |______|    
                                      ||bike||
                                      ||App ||    
                                      ||    ||    
                                      ||    ||    
                                      |------|   
                                      |  ( ) |
                                      
 Hardware prototype attached to bike that provides real time information :
1) GPS chipset to provide real navigation data
2) Fuel sensor(intercept data from bike's fuel sensor receptors)
3) Bluetooh chipset to transmit data as packets to smartphone

Bike App in smartphone:
Get all the information packets from the hardware using BT dedicated channel.

App permissions:
1) BT chipset in device
2) Notification permission (for fuel/mileage update, service update)
