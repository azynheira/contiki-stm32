                              1 ;--------------------------------------------------------
                              2 ; File Created by SDCC : free open source ANSI-C Compiler
                              3 ; Version 3.1.1 #7100 (Apr  1 2013) (Linux)
                              4 ; This file was generated Tue Apr 23 09:41:32 2013
                              5 ;--------------------------------------------------------
                              6 	.module hello_world
                              7 	.optsdcc -mmcs51 --model-large
                              8 	
                              9 ;--------------------------------------------------------
                             10 ; Public variables in this module
                             11 ;--------------------------------------------------------
                             12 	.globl _autostart_processes
                             13 	.globl _printf
                             14 	.globl _IRCON2_P2IF
                             15 	.globl _IRCON2_UTX0IF
                             16 	.globl _IRCON2_UTX1IF
                             17 	.globl _IRCON2_P1IF
                             18 	.globl _IRCON2_WDTIF
                             19 	.globl _CY
                             20 	.globl _AC
                             21 	.globl _F0
                             22 	.globl _RS1
                             23 	.globl _RS0
                             24 	.globl _OV
                             25 	.globl _F1
                             26 	.globl _P
                             27 	.globl _IRCON_DMAIF
                             28 	.globl _IRCON_T1IF
                             29 	.globl _IRCON_T2IF
                             30 	.globl _IRCON_T3IF
                             31 	.globl _IRCON_T4IF
                             32 	.globl _IRCON_P0IF
                             33 	.globl _IRCON_STIF
                             34 	.globl _IEN1_DMAIE
                             35 	.globl _IEN1_T1IE
                             36 	.globl _IEN1_T2IE
                             37 	.globl _IEN1_T3IE
                             38 	.globl _IEN1_T4IE
                             39 	.globl _IEN1_P0IE
                             40 	.globl _IEN0_RFERRIE
                             41 	.globl _IEN0_ADCIE
                             42 	.globl _IEN0_URX0IE
                             43 	.globl _IEN0_URX1IE
                             44 	.globl _IEN0_ENCIE
                             45 	.globl _IEN0_STIE
                             46 	.globl _IEN0_EA
                             47 	.globl _EA
                             48 	.globl _P2_4
                             49 	.globl _P2_3
                             50 	.globl _P2_2
                             51 	.globl _P2_1
                             52 	.globl _P2_0
                             53 	.globl _S0CON_ENCIF_0
                             54 	.globl _S0CON_ENCIF_1
                             55 	.globl _P1_7
                             56 	.globl _P1_6
                             57 	.globl _P1_5
                             58 	.globl _P1_4
                             59 	.globl _P1_3
                             60 	.globl _P1_2
                             61 	.globl _P1_1
                             62 	.globl _P1_0
                             63 	.globl _TCON_IT0
                             64 	.globl _TCON_RFERRIF
                             65 	.globl _TCON_IT1
                             66 	.globl _TCON_URX0IF
                             67 	.globl _TCON_ADCIF
                             68 	.globl _TCON_URX1IF
                             69 	.globl _P0_0
                             70 	.globl _P0_1
                             71 	.globl _P0_2
                             72 	.globl _P0_3
                             73 	.globl _P0_4
                             74 	.globl _P0_5
                             75 	.globl _P0_6
                             76 	.globl _P0_7
                             77 	.globl _P2DIR
                             78 	.globl _P1DIR
                             79 	.globl _P0DIR
                             80 	.globl _U1GCR
                             81 	.globl _U1UCR
                             82 	.globl _U1BAUD
                             83 	.globl _U1BUF
                             84 	.globl _U1CSR
                             85 	.globl _P2INP
                             86 	.globl _P1INP
                             87 	.globl _P2SEL
                             88 	.globl _P1SEL
                             89 	.globl _P0SEL
                             90 	.globl _ADCCFG
                             91 	.globl _PERCFG
                             92 	.globl _B
                             93 	.globl _T4CC1
                             94 	.globl _T4CCTL1
                             95 	.globl _T4CC0
                             96 	.globl _T4CCTL0
                             97 	.globl _T4CTL
                             98 	.globl _T4CNT
                             99 	.globl _RFIF
                            100 	.globl _IRCON2
                            101 	.globl _T1CCTL2
                            102 	.globl _T1CCTL1
                            103 	.globl _T1CCTL0
                            104 	.globl _T1CTL
                            105 	.globl _T1CNTH
                            106 	.globl _T1CNTL
                            107 	.globl _RFST
                            108 	.globl _ACC
                            109 	.globl _T1CC2H
                            110 	.globl _T1CC2L
                            111 	.globl _T1CC1H
                            112 	.globl _T1CC1L
                            113 	.globl _T1CC0H
                            114 	.globl _T1CC0L
                            115 	.globl _RFD
                            116 	.globl _TIMIF
                            117 	.globl _DMAREQ
                            118 	.globl _DMAARM
                            119 	.globl _DMA0CFGH
                            120 	.globl _DMA0CFGL
                            121 	.globl _DMA1CFGH
                            122 	.globl _DMA1CFGL
                            123 	.globl _DMAIRQ
                            124 	.globl _PSW
                            125 	.globl _T3CC1
                            126 	.globl _T3CCTL1
                            127 	.globl _T3CC0
                            128 	.globl _T3CCTL0
                            129 	.globl _T3CTL
                            130 	.globl _T3CNT
                            131 	.globl _WDCTL
                            132 	.globl _T2CON
                            133 	.globl _MEMCTR
                            134 	.globl _CLKCON
                            135 	.globl _U0GCR
                            136 	.globl _U0UCR
                            137 	.globl _T2CNF
                            138 	.globl _U0BAUD
                            139 	.globl _U0BUF
                            140 	.globl _IRCON
                            141 	.globl _SLEEP
                            142 	.globl _RNDH
                            143 	.globl _RNDL
                            144 	.globl _ADCH
                            145 	.globl _ADCL
                            146 	.globl _IP1
                            147 	.globl _IEN1
                            148 	.globl _RCCTL
                            149 	.globl _ADCCON3
                            150 	.globl _ADCCON2
                            151 	.globl _ADCCON1
                            152 	.globl _ENCCS
                            153 	.globl _ENCDO
                            154 	.globl _ENCDI
                            155 	.globl _FWDATA
                            156 	.globl _FCTL
                            157 	.globl _FADDRH
                            158 	.globl _FADDRL
                            159 	.globl _FWT
                            160 	.globl _IP0
                            161 	.globl _IEN0
                            162 	.globl _IE
                            163 	.globl _T2THD
                            164 	.globl _T2TLD
                            165 	.globl _T2CAPHPH
                            166 	.globl _T2CAPLPL
                            167 	.globl _T2OF2
                            168 	.globl _T2OF1
                            169 	.globl _T2OF0
                            170 	.globl _P2
                            171 	.globl _PSBANK
                            172 	.globl _FMAP
                            173 	.globl _T2PEROF2
                            174 	.globl _T2PEROF1
                            175 	.globl _T2PEROF0
                            176 	.globl _S1CON
                            177 	.globl _IEN2
                            178 	.globl _HSRC
                            179 	.globl _S0CON
                            180 	.globl _ST2
                            181 	.globl _ST1
                            182 	.globl _ST0
                            183 	.globl _T2CMP
                            184 	.globl __XPAGE
                            185 	.globl _DPS
                            186 	.globl _RFIM
                            187 	.globl _P1
                            188 	.globl _P0INP
                            189 	.globl _P1IEN
                            190 	.globl _PICTL
                            191 	.globl _P2IFG
                            192 	.globl _P1IFG
                            193 	.globl _P0IFG
                            194 	.globl _TCON
                            195 	.globl _PCON
                            196 	.globl _U0CSR
                            197 	.globl _DPH1
                            198 	.globl _DPL1
                            199 	.globl _DPH0
                            200 	.globl _DPL0
                            201 	.globl _SP
                            202 	.globl _P0
                            203 	.globl _hello_world_process
                            204 	.globl _ADC_SHADOW
                            205 	.globl _U1BUF_SHADOW
                            206 	.globl _RFD_SHADOW
                            207 	.globl _U0BUF_SHADOW
                            208 	.globl _RFSTATUS
                            209 	.globl _CHIPID
                            210 	.globl _CHVER
                            211 	.globl _FSMTC1
                            212 	.globl _RXFIFOCNT
                            213 	.globl _IOCFG3
                            214 	.globl _IOCFG2
                            215 	.globl _IOCFG1
                            216 	.globl _IOCFG0
                            217 	.globl _SHORTADDRL
                            218 	.globl _SHORTADDRH
                            219 	.globl _PANIDL
                            220 	.globl _PANIDH
                            221 	.globl _IEEE_ADDR7
                            222 	.globl _IEEE_ADDR6
                            223 	.globl _IEEE_ADDR5
                            224 	.globl _IEEE_ADDR4
                            225 	.globl _IEEE_ADDR3
                            226 	.globl _IEEE_ADDR2
                            227 	.globl _IEEE_ADDR1
                            228 	.globl _IEEE_ADDR0
                            229 	.globl _DACTSTL
                            230 	.globl _DACTSTH
                            231 	.globl _ADCTSTL
                            232 	.globl _ADCTSTH
                            233 	.globl _FSMSTATE
                            234 	.globl _AGCCTRLL
                            235 	.globl _AGCCTRLH
                            236 	.globl _MANORL
                            237 	.globl _MANORH
                            238 	.globl _MANANDL
                            239 	.globl _MANANDH
                            240 	.globl _FSMTCL
                            241 	.globl _FSMTCH
                            242 	.globl _RFPWR
                            243 	.globl _CSPT
                            244 	.globl _CSPCTRL
                            245 	.globl _CSPZ
                            246 	.globl _CSPY
                            247 	.globl _CSPX
                            248 	.globl _FSCTRLL
                            249 	.globl _FSCTRLH
                            250 	.globl _RXCTRL1L
                            251 	.globl _RXCTRL1H
                            252 	.globl _RXCTRL0L
                            253 	.globl _RXCTRL0H
                            254 	.globl _TXCTRLL
                            255 	.globl _TXCTRLH
                            256 	.globl _SYNCWORDL
                            257 	.globl _SYNCWORDH
                            258 	.globl _RSSIL
                            259 	.globl _RSSIH
                            260 	.globl _MDMCTRL1L
                            261 	.globl _MDMCTRL1H
                            262 	.globl _MDMCTRL0L
                            263 	.globl _MDMCTRL0H
                            264 ;--------------------------------------------------------
                            265 ; special function registers
                            266 ;--------------------------------------------------------
                            267 	.area RSEG    (ABS,DATA)
   0000                     268 	.org 0x0000
                    0080    269 _P0	=	0x0080
                    0081    270 _SP	=	0x0081
                    0082    271 _DPL0	=	0x0082
                    0083    272 _DPH0	=	0x0083
                    0084    273 _DPL1	=	0x0084
                    0085    274 _DPH1	=	0x0085
                    0086    275 _U0CSR	=	0x0086
                    0087    276 _PCON	=	0x0087
                    0088    277 _TCON	=	0x0088
                    0089    278 _P0IFG	=	0x0089
                    008A    279 _P1IFG	=	0x008a
                    008B    280 _P2IFG	=	0x008b
                    008C    281 _PICTL	=	0x008c
                    008D    282 _P1IEN	=	0x008d
                    008F    283 _P0INP	=	0x008f
                    0090    284 _P1	=	0x0090
                    0091    285 _RFIM	=	0x0091
                    0092    286 _DPS	=	0x0092
                    0093    287 __XPAGE	=	0x0093
                    0094    288 _T2CMP	=	0x0094
                    0095    289 _ST0	=	0x0095
                    0096    290 _ST1	=	0x0096
                    0097    291 _ST2	=	0x0097
                    0098    292 _S0CON	=	0x0098
                    0099    293 _HSRC	=	0x0099
                    009A    294 _IEN2	=	0x009a
                    009B    295 _S1CON	=	0x009b
                    009C    296 _T2PEROF0	=	0x009c
                    009D    297 _T2PEROF1	=	0x009d
                    009E    298 _T2PEROF2	=	0x009e
                    009F    299 _FMAP	=	0x009f
                    009F    300 _PSBANK	=	0x009f
                    00A0    301 _P2	=	0x00a0
                    00A1    302 _T2OF0	=	0x00a1
                    00A2    303 _T2OF1	=	0x00a2
                    00A3    304 _T2OF2	=	0x00a3
                    00A4    305 _T2CAPLPL	=	0x00a4
                    00A5    306 _T2CAPHPH	=	0x00a5
                    00A6    307 _T2TLD	=	0x00a6
                    00A7    308 _T2THD	=	0x00a7
                    00A8    309 _IE	=	0x00a8
                    00A8    310 _IEN0	=	0x00a8
                    00A9    311 _IP0	=	0x00a9
                    00AB    312 _FWT	=	0x00ab
                    00AC    313 _FADDRL	=	0x00ac
                    00AD    314 _FADDRH	=	0x00ad
                    00AE    315 _FCTL	=	0x00ae
                    00AF    316 _FWDATA	=	0x00af
                    00B1    317 _ENCDI	=	0x00b1
                    00B2    318 _ENCDO	=	0x00b2
                    00B3    319 _ENCCS	=	0x00b3
                    00B4    320 _ADCCON1	=	0x00b4
                    00B5    321 _ADCCON2	=	0x00b5
                    00B6    322 _ADCCON3	=	0x00b6
                    00B7    323 _RCCTL	=	0x00b7
                    00B8    324 _IEN1	=	0x00b8
                    00B9    325 _IP1	=	0x00b9
                    00BA    326 _ADCL	=	0x00ba
                    00BB    327 _ADCH	=	0x00bb
                    00BC    328 _RNDL	=	0x00bc
                    00BD    329 _RNDH	=	0x00bd
                    00BE    330 _SLEEP	=	0x00be
                    00C0    331 _IRCON	=	0x00c0
                    00C1    332 _U0BUF	=	0x00c1
                    00C2    333 _U0BAUD	=	0x00c2
                    00C3    334 _T2CNF	=	0x00c3
                    00C4    335 _U0UCR	=	0x00c4
                    00C5    336 _U0GCR	=	0x00c5
                    00C6    337 _CLKCON	=	0x00c6
                    00C7    338 _MEMCTR	=	0x00c7
                    00C8    339 _T2CON	=	0x00c8
                    00C9    340 _WDCTL	=	0x00c9
                    00CA    341 _T3CNT	=	0x00ca
                    00CB    342 _T3CTL	=	0x00cb
                    00CC    343 _T3CCTL0	=	0x00cc
                    00CD    344 _T3CC0	=	0x00cd
                    00CE    345 _T3CCTL1	=	0x00ce
                    00CF    346 _T3CC1	=	0x00cf
                    00D0    347 _PSW	=	0x00d0
                    00D1    348 _DMAIRQ	=	0x00d1
                    00D2    349 _DMA1CFGL	=	0x00d2
                    00D3    350 _DMA1CFGH	=	0x00d3
                    00D4    351 _DMA0CFGL	=	0x00d4
                    00D5    352 _DMA0CFGH	=	0x00d5
                    00D6    353 _DMAARM	=	0x00d6
                    00D7    354 _DMAREQ	=	0x00d7
                    00D8    355 _TIMIF	=	0x00d8
                    00D9    356 _RFD	=	0x00d9
                    00DA    357 _T1CC0L	=	0x00da
                    00DB    358 _T1CC0H	=	0x00db
                    00DC    359 _T1CC1L	=	0x00dc
                    00DD    360 _T1CC1H	=	0x00dd
                    00DE    361 _T1CC2L	=	0x00de
                    00DF    362 _T1CC2H	=	0x00df
                    00E0    363 _ACC	=	0x00e0
                    00E1    364 _RFST	=	0x00e1
                    00E2    365 _T1CNTL	=	0x00e2
                    00E3    366 _T1CNTH	=	0x00e3
                    00E4    367 _T1CTL	=	0x00e4
                    00E5    368 _T1CCTL0	=	0x00e5
                    00E6    369 _T1CCTL1	=	0x00e6
                    00E7    370 _T1CCTL2	=	0x00e7
                    00E8    371 _IRCON2	=	0x00e8
                    00E9    372 _RFIF	=	0x00e9
                    00EA    373 _T4CNT	=	0x00ea
                    00EB    374 _T4CTL	=	0x00eb
                    00EC    375 _T4CCTL0	=	0x00ec
                    00ED    376 _T4CC0	=	0x00ed
                    00EE    377 _T4CCTL1	=	0x00ee
                    00EF    378 _T4CC1	=	0x00ef
                    00F0    379 _B	=	0x00f0
                    00F1    380 _PERCFG	=	0x00f1
                    00F2    381 _ADCCFG	=	0x00f2
                    00F3    382 _P0SEL	=	0x00f3
                    00F4    383 _P1SEL	=	0x00f4
                    00F5    384 _P2SEL	=	0x00f5
                    00F6    385 _P1INP	=	0x00f6
                    00F7    386 _P2INP	=	0x00f7
                    00F8    387 _U1CSR	=	0x00f8
                    00F9    388 _U1BUF	=	0x00f9
                    00FA    389 _U1BAUD	=	0x00fa
                    00FB    390 _U1UCR	=	0x00fb
                    00FC    391 _U1GCR	=	0x00fc
                    00FD    392 _P0DIR	=	0x00fd
                    00FE    393 _P1DIR	=	0x00fe
                    00FF    394 _P2DIR	=	0x00ff
                            395 ;--------------------------------------------------------
                            396 ; special function bits
                            397 ;--------------------------------------------------------
                            398 	.area RSEG    (ABS,DATA)
   0000                     399 	.org 0x0000
                    0087    400 _P0_7	=	0x0087
                    0086    401 _P0_6	=	0x0086
                    0085    402 _P0_5	=	0x0085
                    0084    403 _P0_4	=	0x0084
                    0083    404 _P0_3	=	0x0083
                    0082    405 _P0_2	=	0x0082
                    0081    406 _P0_1	=	0x0081
                    0080    407 _P0_0	=	0x0080
                    008F    408 _TCON_URX1IF	=	0x008f
                    008D    409 _TCON_ADCIF	=	0x008d
                    008B    410 _TCON_URX0IF	=	0x008b
                    008A    411 _TCON_IT1	=	0x008a
                    0089    412 _TCON_RFERRIF	=	0x0089
                    0088    413 _TCON_IT0	=	0x0088
                    0090    414 _P1_0	=	0x0090
                    0091    415 _P1_1	=	0x0091
                    0092    416 _P1_2	=	0x0092
                    0093    417 _P1_3	=	0x0093
                    0094    418 _P1_4	=	0x0094
                    0095    419 _P1_5	=	0x0095
                    0096    420 _P1_6	=	0x0096
                    0097    421 _P1_7	=	0x0097
                    0099    422 _S0CON_ENCIF_1	=	0x0099
                    0098    423 _S0CON_ENCIF_0	=	0x0098
                    00A0    424 _P2_0	=	0x00a0
                    00A1    425 _P2_1	=	0x00a1
                    00A2    426 _P2_2	=	0x00a2
                    00A3    427 _P2_3	=	0x00a3
                    00A4    428 _P2_4	=	0x00a4
                    00AF    429 _EA	=	0x00af
                    00AF    430 _IEN0_EA	=	0x00af
                    00AD    431 _IEN0_STIE	=	0x00ad
                    00AC    432 _IEN0_ENCIE	=	0x00ac
                    00AB    433 _IEN0_URX1IE	=	0x00ab
                    00AA    434 _IEN0_URX0IE	=	0x00aa
                    00A9    435 _IEN0_ADCIE	=	0x00a9
                    00A8    436 _IEN0_RFERRIE	=	0x00a8
                    00BD    437 _IEN1_P0IE	=	0x00bd
                    00BC    438 _IEN1_T4IE	=	0x00bc
                    00BB    439 _IEN1_T3IE	=	0x00bb
                    00BA    440 _IEN1_T2IE	=	0x00ba
                    00B9    441 _IEN1_T1IE	=	0x00b9
                    00B8    442 _IEN1_DMAIE	=	0x00b8
                    00C7    443 _IRCON_STIF	=	0x00c7
                    00C5    444 _IRCON_P0IF	=	0x00c5
                    00C4    445 _IRCON_T4IF	=	0x00c4
                    00C3    446 _IRCON_T3IF	=	0x00c3
                    00C2    447 _IRCON_T2IF	=	0x00c2
                    00C1    448 _IRCON_T1IF	=	0x00c1
                    00C0    449 _IRCON_DMAIF	=	0x00c0
                    00D0    450 _P	=	0x00d0
                    00D1    451 _F1	=	0x00d1
                    00D2    452 _OV	=	0x00d2
                    00D3    453 _RS0	=	0x00d3
                    00D4    454 _RS1	=	0x00d4
                    00D5    455 _F0	=	0x00d5
                    00D6    456 _AC	=	0x00d6
                    00D7    457 _CY	=	0x00d7
                    00EC    458 _IRCON2_WDTIF	=	0x00ec
                    00EB    459 _IRCON2_P1IF	=	0x00eb
                    00EA    460 _IRCON2_UTX1IF	=	0x00ea
                    00E9    461 _IRCON2_UTX0IF	=	0x00e9
                    00E8    462 _IRCON2_P2IF	=	0x00e8
                            463 ;--------------------------------------------------------
                            464 ; overlayable register banks
                            465 ;--------------------------------------------------------
                            466 	.area REG_BANK_0	(REL,OVR,DATA)
   0000                     467 	.ds 8
                            468 ;--------------------------------------------------------
                            469 ; internal ram data
                            470 ;--------------------------------------------------------
                            471 	.area DSEG    (DATA)
                            472 ;--------------------------------------------------------
                            473 ; overlayable items in internal ram 
                            474 ;--------------------------------------------------------
                            475 	.area OSEG    (OVR,DATA)
                            476 ;--------------------------------------------------------
                            477 ; indirectly addressable internal ram data
                            478 ;--------------------------------------------------------
                            479 	.area ISEG    (DATA)
                            480 ;--------------------------------------------------------
                            481 ; absolute internal ram data
                            482 ;--------------------------------------------------------
                            483 	.area IABS    (ABS,DATA)
                            484 	.area IABS    (ABS,DATA)
                            485 ;--------------------------------------------------------
                            486 ; bit data
                            487 ;--------------------------------------------------------
                            488 	.area BSEG    (BIT)
                            489 ;--------------------------------------------------------
                            490 ; paged external ram data
                            491 ;--------------------------------------------------------
                            492 	.area PSEG    (PAG,XDATA)
                            493 ;--------------------------------------------------------
                            494 ; external ram data
                            495 ;--------------------------------------------------------
                            496 	.area XSEG    (XDATA)
                    DF02    497 _MDMCTRL0H	=	0xdf02
                    DF03    498 _MDMCTRL0L	=	0xdf03
                    DF04    499 _MDMCTRL1H	=	0xdf04
                    DF05    500 _MDMCTRL1L	=	0xdf05
                    DF06    501 _RSSIH	=	0xdf06
                    DF07    502 _RSSIL	=	0xdf07
                    DF08    503 _SYNCWORDH	=	0xdf08
                    DF09    504 _SYNCWORDL	=	0xdf09
                    DF0A    505 _TXCTRLH	=	0xdf0a
                    DF0B    506 _TXCTRLL	=	0xdf0b
                    DF0C    507 _RXCTRL0H	=	0xdf0c
                    DF0D    508 _RXCTRL0L	=	0xdf0d
                    DF0E    509 _RXCTRL1H	=	0xdf0e
                    DF0F    510 _RXCTRL1L	=	0xdf0f
                    DF10    511 _FSCTRLH	=	0xdf10
                    DF11    512 _FSCTRLL	=	0xdf11
                    DF12    513 _CSPX	=	0xdf12
                    DF13    514 _CSPY	=	0xdf13
                    DF14    515 _CSPZ	=	0xdf14
                    DF15    516 _CSPCTRL	=	0xdf15
                    DF16    517 _CSPT	=	0xdf16
                    DF17    518 _RFPWR	=	0xdf17
                    DF20    519 _FSMTCH	=	0xdf20
                    DF21    520 _FSMTCL	=	0xdf21
                    DF22    521 _MANANDH	=	0xdf22
                    DF23    522 _MANANDL	=	0xdf23
                    DF24    523 _MANORH	=	0xdf24
                    DF25    524 _MANORL	=	0xdf25
                    DF26    525 _AGCCTRLH	=	0xdf26
                    DF27    526 _AGCCTRLL	=	0xdf27
                    DF39    527 _FSMSTATE	=	0xdf39
                    DF3A    528 _ADCTSTH	=	0xdf3a
                    DF3B    529 _ADCTSTL	=	0xdf3b
                    DF3C    530 _DACTSTH	=	0xdf3c
                    DF3D    531 _DACTSTL	=	0xdf3d
                    DF43    532 _IEEE_ADDR0	=	0xdf43
                    DF44    533 _IEEE_ADDR1	=	0xdf44
                    DF45    534 _IEEE_ADDR2	=	0xdf45
                    DF46    535 _IEEE_ADDR3	=	0xdf46
                    DF47    536 _IEEE_ADDR4	=	0xdf47
                    DF48    537 _IEEE_ADDR5	=	0xdf48
                    DF49    538 _IEEE_ADDR6	=	0xdf49
                    DF4A    539 _IEEE_ADDR7	=	0xdf4a
                    DF4B    540 _PANIDH	=	0xdf4b
                    DF4C    541 _PANIDL	=	0xdf4c
                    DF4D    542 _SHORTADDRH	=	0xdf4d
                    DF4E    543 _SHORTADDRL	=	0xdf4e
                    DF4F    544 _IOCFG0	=	0xdf4f
                    DF50    545 _IOCFG1	=	0xdf50
                    DF51    546 _IOCFG2	=	0xdf51
                    DF52    547 _IOCFG3	=	0xdf52
                    DF53    548 _RXFIFOCNT	=	0xdf53
                    DF54    549 _FSMTC1	=	0xdf54
                    DF60    550 _CHVER	=	0xdf60
                    DF61    551 _CHIPID	=	0xdf61
                    DF62    552 _RFSTATUS	=	0xdf62
                    DFC1    553 _U0BUF_SHADOW	=	0xdfc1
                    DFD9    554 _RFD_SHADOW	=	0xdfd9
                    DFF9    555 _U1BUF_SHADOW	=	0xdff9
                    DFBA    556 _ADC_SHADOW	=	0xdfba
                            557 ;--------------------------------------------------------
                            558 ; absolute external ram data
                            559 ;--------------------------------------------------------
                            560 	.area XABS    (ABS,XDATA)
                            561 ;--------------------------------------------------------
                            562 ; external initialized ram data
                            563 ;--------------------------------------------------------
                            564 	.area XISEG   (XDATA)
   EB06                     565 _hello_world_process::
   EB06                     566 	.ds 9
                            567 	.area HOME    (CODE)
                            568 	.area GSINIT0 (CODE)
                            569 	.area GSINIT1 (CODE)
                            570 	.area GSINIT2 (CODE)
                            571 	.area GSINIT3 (CODE)
                            572 	.area GSINIT4 (CODE)
                            573 	.area GSINIT5 (CODE)
                            574 	.area GSINIT  (CODE)
                            575 	.area GSFINAL (CODE)
                            576 	.area CSEG    (CODE)
                            577 ;--------------------------------------------------------
                            578 ; global & static initialisations
                            579 ;--------------------------------------------------------
                            580 	.area HOME    (CODE)
                            581 	.area GSINIT  (CODE)
                            582 	.area GSFINAL (CODE)
                            583 	.area GSINIT  (CODE)
                            584 ;--------------------------------------------------------
                            585 ; Home
                            586 ;--------------------------------------------------------
                            587 	.area HOME    (CODE)
                            588 	.area HOME    (CODE)
                            589 ;--------------------------------------------------------
                            590 ; code
                            591 ;--------------------------------------------------------
                            592 	.area CSEG    (CODE)
                            593 ;------------------------------------------------------------
                            594 ;Allocation info for local variables in function 'process_thread_hello_world_process'
                            595 ;------------------------------------------------------------
                            596 ;ev                        Allocated to stack - _bp -3
                            597 ;data                      Allocated to stack - _bp -6
                            598 ;process_pt                Allocated to registers r5 r6 r7 
                            599 ;PT_YIELD_FLAG             Allocated to registers 
                            600 ;------------------------------------------------------------
                            601 ;	hello_world.c:14: PROCESS_THREAD(hello_world_process, ev, data)
                            602 ;	-----------------------------------------
                            603 ;	 function process_thread_hello_world_process
                            604 ;	-----------------------------------------
   0445                     605 _process_thread_hello_world_process:
                    0007    606 	ar7 = 0x07
                    0006    607 	ar6 = 0x06
                    0005    608 	ar5 = 0x05
                    0004    609 	ar4 = 0x04
                    0003    610 	ar3 = 0x03
                    0002    611 	ar2 = 0x02
                    0001    612 	ar1 = 0x01
                    0000    613 	ar0 = 0x00
   0445 C0 1A               614 	push	_bp
   0447 85 81 1A            615 	mov	_bp,sp
                            616 ;	hello_world.c:17: PROCESS_BEGIN();
   044A AD 82               617 	mov	r5,dpl
   044C AE 83               618 	mov	r6,dph
   044E AF F0               619 	mov	r7,b
   0450 12 5E 53            620 	lcall	__gptrget
   0453 FB                  621 	mov	r3,a
   0454 A3                  622 	inc	dptr
   0455 12 5E 53            623 	lcall	__gptrget
   0458 FC                  624 	mov	r4,a
   0459 BB 00 24            625 	cjne	r3,#0x00,00102$
   045C BC 00 21            626 	cjne	r4,#0x00,00102$
                            627 ;	hello_world.c:19: printf("Hello World!\n");
   045F C0 07               628 	push	ar7
   0461 C0 06               629 	push	ar6
   0463 C0 05               630 	push	ar5
   0465 74 A6               631 	mov	a,#__str_0
   0467 C0 E0               632 	push	acc
   0469 74 B2               633 	mov	a,#(__str_0 >> 8)
   046B C0 E0               634 	push	acc
   046D 74 80               635 	mov	a,#0x80
   046F C0 E0               636 	push	acc
   0471 12 4C CC            637 	lcall	_printf
   0474 15 81               638 	dec	sp
   0476 15 81               639 	dec	sp
   0478 15 81               640 	dec	sp
   047A D0 05               641 	pop	ar5
   047C D0 06               642 	pop	ar6
   047E D0 07               643 	pop	ar7
                            644 ;	hello_world.c:21: PROCESS_END();
   0480                     645 00102$:
   0480 8D 82               646 	mov	dpl,r5
   0482 8E 83               647 	mov	dph,r6
   0484 8F F0               648 	mov	b,r7
   0486 E4                  649 	clr	a
   0487 12 2F DF            650 	lcall	__gptrput
   048A A3                  651 	inc	dptr
   048B E4                  652 	clr	a
   048C 12 2F DF            653 	lcall	__gptrput
   048F 75 82 03            654 	mov	dpl,#0x03
   0492 D0 1A               655 	pop	_bp
   0494 22                  656 	ret
                            657 	.area CSEG    (CODE)
                            658 	.area CONST   (CODE)
   B2A0                     659 _autostart_processes:
   B2A0 06 EB 00            660 	.byte _hello_world_process,(_hello_world_process >> 8),#0x00
                            661 ; generic printIvalPtr
   B2A3 00 00 00            662 	.byte #0x00,#0x00,#0x00
   B2A6                     663 __str_0:
   B2A6 48 65 6C 6C 6F 20   664 	.ascii "Hello World!"
        57 6F 72 6C 64 21
   B2B2 0A                  665 	.db 0x0A
   B2B3 00                  666 	.db 0x00
                            667 	.area XINIT   (CODE)
   B37A                     668 __xinit__hello_world_process:
                            669 ; generic printIvalPtr
   B37A 00 00 00            670 	.byte #0x00,#0x00,#0x00
   B37D 45 04               671 	.byte _process_thread_hello_world_process,(_process_thread_hello_world_process >> 8)
   B37F 00 00               672 	.byte #0x00,#0x00	; 0
   B381 00                  673 	.db #0x00	; 0
   B382 00                  674 	.db #0x00	; 0
                            675 	.area CABS    (ABS,CODE)
